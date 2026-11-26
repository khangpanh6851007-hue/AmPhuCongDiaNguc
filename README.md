# QUỶ MÔN QUAN 12.0 — Thiên Giới & Âm Phủ OS

Hệ thống quản lý Âm Phủ dạng web, giao diện tiếng Việt, thiết kế responsive cho máy tính và thiết bị di động.

## Các phân hệ chính

- **Trung tâm điều hành:** bảng tổng quan và trạng thái vận hành.
- **Gương Nghiệp Kính:** mô phỏng quy trình xét duyệt hồ sơ.
- **Sổ Sinh Tử:** tạo, tra cứu, lọc và quản lý hồ sơ.
- **Ngục Môn:** bản đồ và dữ liệu mô phỏng 100 tầng.
- **Công Hội và nhiệm vụ:** thành viên, nhiệm vụ, công trạng và lịch sử hoạt động.
- **AI và phân tích (17.0):** tổng hợp số liệu, cảnh báo hồ sơ trùng lặp, phân tích tình trạng Ngục Môn và trợ lý quản trị nội bộ.
- **Ultimate Underworld OS (20.0):** trung tâm điều hành Thiên Giới – Âm Phủ, bản đồ phân hệ, báo cáo tập trung và khu vực kiểm soát dữ liệu.
- **Thiên Giới quản lý Âm Phủ:** tiếp nhận báo cáo, ban hành chỉ thị, phê duyệt đề xuất và theo dõi vận hành.

> Thiên Giới là phân hệ giám sát nghiệp vụ; dự án không tạo hệ thống 100 cấp chức danh hay phong quan.

## Công nghệ và lưu trữ

- HTML, CSS và JavaScript phía trình duyệt.
- Giao diện sử dụng Tailwind CSS qua CDN cùng Google Fonts.
- Dữ liệu hiện được lưu cục bộ bằng `localStorage` trên trình duyệt đang sử dụng.
- Phân tích AI hiện là trợ lý nội bộ dựa trên dữ liệu và quy tắc trong ứng dụng; chưa phải dịch vụ AI trực tuyến.
- Workflow GitHub Pages bên dưới chỉ triển khai website tĩnh. Nó không tự tạo máy chủ, cơ sở dữ liệu hoặc đồng bộ nhiều thiết bị.

## Chạy tại máy

1. Đặt file website chính tại thư mục gốc repository và đặt tên là `index.html`.
2. Mở `index.html` bằng trình duyệt hiện đại.
3. Cho phép JavaScript và kết nối Internet để tải các tài nguyên CDN (Tailwind CSS và Google Fonts).

## Triển khai GitHub Pages

1. Tạo repository GitHub.
2. Đưa `index.html` và `README.md` vào thư mục gốc.
3. Đặt workflow này tại đúng đường dẫn `.github/workflows/deploy.yml`.
4. Vào **Settings → Pages** và chọn **GitHub Actions** làm Build and deployment source.
5. Push lên nhánh `main` (hoặc chạy thủ công trong tab **Actions**). Workflow sẽ build và deploy website lên GitHub Pages.

Nếu repository dùng nhánh mặc định khác `main`, hãy sửa giá trị `branches` trong workflow cho phù hợp.

## Các file trong gói GitHub 2026

- `README.md`
- `.github/workflows/deploy.yml`

File website `index.html` là tài sản dự án hiện có, không nằm trong gói hai file cấu hình/tài liệu này.
