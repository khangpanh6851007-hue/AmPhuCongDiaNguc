# QUỶ MÔN QUAN 11.2 — Sổ Sinh Tử Truyền Kiếp

Ứng dụng web tĩnh mô phỏng hệ thống quản lý âm phủ, hồ sơ linh hồn và quá trình xét xử trong giao diện tiếng Việt.

## Giới thiệu

QUỶ MÔN QUAN 11.2 là ứng dụng chạy trực tiếp trên trình duyệt. Giao diện sử dụng HTML, CSS, JavaScript, Tailwind CSS CDN và Google Fonts. Không cần máy chủ ứng dụng hoặc bước build riêng.

## Tính năng chính

- Bảng điều khiển tổng quan và thống kê hồ sơ.
- Tòa án Diêm Vương AI với biểu mẫu nhập hồ sơ và mô phỏng phán quyết.
- Sổ Sinh Tử: tra cứu, lọc, sắp xếp, chỉnh sửa và quản lý trạng thái hồ sơ.
- Danh sách tên bị hạn chế được kiểm tra khi lập hồ sơ phán quyết và khi nhập/đổi tên hồ sơ liên quan.
- Bản đồ các tầng Ngục Môn và thông tin hồ sơ đang chịu phạt.
- Trạm công đức, nhiệm vụ truy bắt và nhật ký hoạt động.
- Sao lưu/khôi phục dữ liệu JSON; một số dữ liệu được lưu cục bộ bằng `localStorage` trên trình duyệt hiện tại.
- Giao diện responsive, hỗ trợ màn hình điện thoại và máy tính.

> Đây là ứng dụng mô phỏng/giải trí. Các điểm nghiệp lực, phân loại và thời hạn trong ứng dụng là quy tắc giả tưởng, không phải kết luận pháp lý hay đánh giá con người.

## Cấu trúc repository

```text
.
├── index.html
├── README.md
└── .github/
    └── workflows/
        └── deploy.yml
```

## Chạy thử trên máy

1. Tải hoặc clone repository.
2. Mở `index.html` bằng trình duyệt hiện đại.
3. Có thể dùng tiện ích Live Server trong VS Code để chạy qua máy chủ tĩnh khi phát triển.

Ứng dụng tải Tailwind CSS và phông chữ từ CDN, vì vậy một số hiệu ứng/giao diện cần kết nối Internet.

## Triển khai GitHub Pages

Workflow tại `.github/workflows/deploy.yml` tự động triển khai website khi có push lên nhánh `main` hoặc khi chạy thủ công.

1. Đưa `index.html`, `README.md` và thư mục `.github/workflows/` lên repository GitHub.
2. Vào **Settings → Pages**.
3. Trong **Build and deployment**, chọn **GitHub Actions** làm nguồn triển khai.
4. Push commit lên nhánh `main` hoặc chạy workflow **Deploy to GitHub Pages** trong tab **Actions**.
5. Sau khi workflow hoàn tất, mở URL GitHub Pages hiển thị trong **Settings → Pages**.

## Dữ liệu và quyền riêng tư

- Dữ liệu `localStorage` nằm trong trình duyệt và thiết bị đang sử dụng; dữ liệu không tự đồng bộ giữa các thiết bị.
- Xóa dữ liệu trình duyệt hoặc đổi trình duyệt có thể làm mất dữ liệu chưa sao lưu.
- Dùng chức năng sao lưu JSON trong ứng dụng để lưu bản dự phòng và khôi phục khi cần.
- Không nhập thông tin cá nhân nhạy cảm hoặc dữ liệu thật vào bản mô phỏng công khai.

## Công nghệ

- HTML5
- CSS3
- JavaScript thuần
- Tailwind CSS CDN
- Google Fonts
- Browser `localStorage` và JSON import/export
