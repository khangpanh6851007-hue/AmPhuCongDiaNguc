# QUỶ MÔN QUAN — GitHub Pages 2026

Website mô phỏng **QUỶ MÔN QUAN**, đóng gói dưới dạng một trang HTML tĩnh để triển khai bằng GitHub Pages.

## Nội dung

- `index.html` — website QUỶ MÔN QUAN phiên bản 11.0.
- `.github/workflows/deploy.yml` — GitHub Actions workflow tự động triển khai lên GitHub Pages.

## Đưa dự án lên GitHub

1. Tạo repository mới trên GitHub.
2. Tải các tệp trong thư mục này lên repository, giữ nguyên cấu trúc `.github/workflows/deploy.yml`.
3. Commit và push lên nhánh `main`.
4. Mở **Settings → Pages** của repository.
5. Trong **Build and deployment**, chọn **GitHub Actions**.
6. Mở tab **Actions** và chờ workflow **Deploy to GitHub Pages** chạy xong.
7. Địa chỉ website sẽ có dạng `https://<tên-tài-khoản>.github.io/<tên-repository>/`.

## Cập nhật website

Thay nội dung `index.html` bằng bản HTML mới, sau đó commit và push lên nhánh `main`. Workflow sẽ tự chạy lại.

## Lưu ý

- Đây là website tĩnh; workflow chỉ xuất bản các tệp trong repository, không tạo máy chủ backend.
- Dữ liệu lưu bằng `localStorage` nằm trên trình duyệt và thiết bị đang sử dụng; không tự đồng bộ giữa các thiết bị.
- Website có thể sử dụng thư viện, font hoặc tài nguyên CDN bên ngoài nên cần kết nối Internet để tải các tài nguyên đó.
- Không đưa mật khẩu, khóa API hoặc dữ liệu cá nhân nhạy cảm vào repository công khai.

## Phiên bản

- Gói triển khai: GitHub Pages 2026
- Website: QUỶ MÔN QUAN 11.0
