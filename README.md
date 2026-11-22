# 🔥 UNDERWORLD OS 8.0

**Hệ điều hành quản lý Âm phủ & mô phỏng phán quyết nghiệp lực**  
Phiên bản: **8.0** · Cập nhật tài liệu: **2026** · Ngôn ngữ giao diện: **Tiếng Việt**

UNDERWORLD OS là ứng dụng web mô phỏng thế giới Âm phủ theo phong cách cyberpunk. Ứng dụng cung cấp bảng điều khiển, màn hình xét xử giả lập, sổ sinh tử, bản đồ 18 tầng địa ngục, khu vực Mạnh Bà và nhật ký hoạt động.

> **Lưu ý:** Đây là dự án mô phỏng/giải trí. Điểm nghiệp lực, tội danh, thời hạn và hình phạt trong ứng dụng là dữ liệu hư cấu, không phải đánh giá đạo đức, kết luận pháp lý hay tư vấn chuyên môn về bất kỳ cá nhân nào.

## ✨ Tính năng

- **Tổng quan:** hiển thị số liệu linh hồn, trạng thái và chỉ số nghiệp lực.
- **Tòa Án Diêm Vương AI:** nhập thông tin và thực hiện quy trình phán quyết mô phỏng.
- **Sổ Sinh Tử điện tử:** tạo, xem, chỉnh sửa và quản lý hồ sơ; tìm kiếm theo tên, mã hồ sơ, tội danh hoặc lời khai.
- **Lọc & sắp xếp:** lọc theo tầng địa ngục/trạng thái; sắp xếp theo mới nhất, cũ nhất, nghiệp lực, thời hạn hoặc tên.
- **Quản lý hàng loạt:** chọn nhiều hồ sơ và cập nhật trạng thái cùng lúc.
- **Bản đồ 18 tầng địa ngục:** xem thông tin từng tầng, cai ngục và hình phạt mô phỏng.
- **Quán Trà Mạnh Bà:** khu vực mô phỏng quy trình uống trà và đầu thai.
- **Nhật ký hệ thống:** theo dõi hoạt động và xuất nhật ký.
- **Sao lưu & khôi phục:** xuất/nhập dữ liệu hồ sơ bằng JSON; xuất danh sách hồ sơ dạng CSV.
- **Giao diện responsive:** hỗ trợ màn hình máy tính và thiết bị di động.

## 🚀 Chạy ứng dụng

### Cách 1: Mở trực tiếp

1. Tải hoặc clone repository về máy.
2. Mở file `index.html` bằng trình duyệt hiện đại.
3. Cho phép trình duyệt tải các tài nguyên bên ngoài nếu muốn hiển thị đầy đủ giao diện.

### Cách 2: Chạy bằng máy chủ local

Nếu trình duyệt hạn chế một số chức năng khi mở file trực tiếp, hãy chạy một máy chủ web tĩnh trong thư mục dự án. Ví dụ với Python:

```bash
python -m http.server 8000
```

Sau đó truy cập `http://localhost:8000`.

## 🌐 Triển khai bằng GitHub Pages (2026)

1. Tạo một repository trên GitHub.
2. Đưa `index.html` và `README.md` vào thư mục gốc của repository.
3. Mở **Settings → Pages** trong repository.
4. Trong phần **Build and deployment**, chọn **Deploy from a branch**.
5. Chọn nhánh muốn triển khai (thường là `main`) và thư mục `/(root)`, sau đó lưu.
6. Chờ GitHub Pages hoàn tất triển khai; mở URL được hiển thị trong phần Pages.

Mỗi lần cập nhật mã nguồn và push lên nhánh đã chọn, GitHub Pages sẽ triển khai phiên bản mới theo cấu hình repository.

## 🧰 Công nghệ

- HTML5
- CSS3
- JavaScript thuần
- Tailwind CSS qua CDN
- Google Fonts: Cinzel, JetBrains Mono và Space Grotesk
- `localStorage` của trình duyệt để lưu dữ liệu trên thiết bị

## 💾 Dữ liệu & quyền riêng tư

- Hồ sơ được lưu cục bộ trong `localStorage` của trình duyệt; ứng dụng không cần máy chủ cơ sở dữ liệu để chạy các chức năng chính.
- Dữ liệu trên một trình duyệt/thiết bị không tự động đồng bộ sang trình duyệt/thiết bị khác.
- Xóa dữ liệu trang web, dùng chế độ ẩn danh hoặc đổi trình duyệt có thể khiến dữ liệu cục bộ không còn truy cập được.
- Hãy dùng chức năng **Sao lưu dữ liệu** để tải JSON định kỳ và lưu ở nơi an toàn.
- Khi khôi phục JSON, dữ liệu hiện tại sẽ bị thay thế sau khi người dùng xác nhận. Hãy sao lưu trước khi nhập tệp.
- Ứng dụng tải Tailwind CSS và Google Fonts từ CDN; cần kết nối Internet để tải các tài nguyên này.

## 📁 Cấu trúc repository

```text
.
├── index.html   # Ứng dụng UNDERWORLD OS
└── README.md    # Tài liệu dự án
```

## 📝 Ghi chú phiên bản 8.0

- Cập nhật nhận diện giao diện lên UNDERWORLD OS 8.0.
- Loại bỏ phần hướng dẫn triển khai Acode/TrebEdit/GitHub tích hợp trong giao diện ứng dụng.
- Mở rộng tìm kiếm sổ sinh tử và bổ sung bộ lọc/sắp xếp hồ sơ.
- Bổ sung đếm số kết quả phù hợp và giữ các chức năng sao lưu/khôi phục dữ liệu.

## ⚖️ Tuyên bố miễn trừ

UNDERWORLD OS được xây dựng cho mục đích học tập, thử nghiệm giao diện và giải trí. Nội dung mô phỏng không đại diện cho hệ thống pháp luật, tôn giáo hay quan điểm chính thức của bất kỳ tổ chức nào. Không sử dụng ứng dụng để đưa ra quyết định thật về con người.

---

<p align="center">🔥 <strong>UNDERWORLD OS 8.0</strong> · Fictional Underworld Simulation · 2026 🔥</p>
