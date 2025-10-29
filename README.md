# Antivirus Mask Website

Một trang web tĩnh cho sản phẩm khẩu trang kháng khuẩn. Đây là repo chứa mã nguồn front-end (HTML, CSS, assets) của dự án.

## Mô tả

Trang web được xây dựng bằng HTML/CSS tĩnh (không có backend). Mục tiêu: trình bày sản phẩm khẩu trang (sản phẩm, khuyến mãi, thông tin liên hệ, video/ảnh minh họa).

## Tính năng chính

- Thanh header với menu và biểu tượng mạng xã hội
- Banner/hero có hình ảnh và khuyến mãi
- Các section sản phẩm, bộ sưu tập, review, form đăng ký nhận tin
- Hỗ trợ video và media trong thư mục `Assets/`
- Sử dụng Font Awesome cho icon (lưu ý cấu hình, xem phần Troubleshooting)

## Kỹ thuật & Tiện ích

- HTML5, CSS3 (file chính: `index.html`, `Assets/css/styles.css`)
- Hình ảnh và video trong `Assets/images/` và `Assets/videos/`
- Không cần build step — dự án có thể chạy trực tiếp bằng cách mở `index.html` hoặc serve tạm thời bằng một HTTP server

## Cấu trúc thư mục

```
project-root/
├─ index.html
├─ README.md
└─ Assets/
	├─ css/
	│  ├─ reset.css
	│  ├─ base.css
	│  └─ styles.css   # CSS chính
	├─ images/
	└─ videos/
```

## Chạy dự án (cách nhanh)

1. Mở trực tiếp file `index.html` trong trình duyệt (double click hoặc `Open with`)

2. Hoặc serve bằng link host github: `https://mobirise.com/extensions/softwarem4/software-app/`

## Chỉnh sửa nhanh

- CSS chính: `Assets/css/styles.css`
- Thêm/đổi hình ảnh: `Assets/images/`
- Sửa nội dung trang: `index.html`

## Góp ý / Phát triển

Nếu bạn muốn đóng góp các chỉnh sửa nhỏ (CSS, sửa typo, thêm ảnh), hãy fork repo, tạo branch, và nộp pull request. Nên giữ các thay đổi nhỏ và kèm mô tả rõ ràng.

---