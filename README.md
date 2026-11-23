# UNDERWORLD OS 9.0

**Hệ thống quản lý Âm Phủ & Công Hội Quỷ Sứ – Linh Hồn Lập Công**

UNDERWORLD OS 9.0 là ứng dụng web mô phỏng quản lý hồ sơ linh hồn, 18 tầng Địa Ngục, công đức, đầu thai và hệ thống nhiệm vụ truy bắt phạm nhân. Giao diện tiếng Việt, phong cách dark fantasy/neon, hỗ trợ màn hình máy tính và điện thoại.

## ✨ Tính năng

### Trung tâm điều hành
- Thống kê hồ sơ, trạng thái thi hành án và nghiệp lực.
- Theo dõi hoạt động gần đây.
- Truy cập nhanh các phân hệ.

### Tòa án Diêm Vương AI
- Tạo hồ sơ mô phỏng từ tên, tuổi, tội danh và lời khai.
- Tính nghiệp lực, thời hạn án và tầng giam giữ theo dữ liệu trò chơi.
- Có danh sách tên bị hạn chế ghi hồ sơ trong ứng dụng.

### Sổ Sinh Tử điện tử
- Tìm kiếm, lọc theo tầng và trạng thái; sắp xếp hồ sơ.
- Xem, chỉnh sửa và xóa hồ sơ.
- Chọn nhiều hồ sơ để cập nhật trạng thái.
- Sao lưu/khôi phục JSON và xuất CSV.

### Bản đồ 18 tầng Địa Ngục
- Xem thông tin từng tầng, cai ngục, mô tả và hồ sơ đang được ghi nhận tại tầng đó.

### Quán Trà Mạnh Bà & Nạp Công Đức
- Thực hiện hoạt động công đức để giảm số năm án trong mô phỏng.
- Khi đủ điều kiện, cấp vé đầu thai và ghi nhận lựa chọn trà.

### 🎖️ Công Hội Quỷ Sứ & Linh Hồn Lập Công (mới ở 9.0)
- Đăng ký người nhận nhiệm vụ với thân phận **Quỷ sứ** hoặc **Linh hồn tình nguyện**.
- Bảng truy nã lấy các hồ sơ đang ở trạng thái chịu phạt và chưa được ghi nhận áp giải.
- Nhiệm vụ tự phân loại theo hồ sơ: Dễ, Trung bình, Khó và Truy nã đặc biệt.
- Thưởng công trạng tăng theo độ khó: **40 / 100 / 250 / 500**.
- Ghi nhận người áp giải, thời điểm hoàn thành, lịch sử nhiệm vụ và nhật ký hệ thống.
- Công trạng tự động xét cấp bậc theo các mốc sau:

| Cấp bậc | Mốc công trạng |
|---|---:|
| Tân Binh Tuần Ngục | 0 |
| Quỷ Binh Truy Nã | 100 |
| Đội Trưởng Áp Giải | 300 |
| Đô Úy Địa Phủ | 650 |
| Phán Quan Truy Bắt | 1.200 |
| Thống Lĩnh Thiên Lao | 2.000 |
| Đại Nguyên Soái Địa Phủ | 3.500 |

## 🚀 Chạy ứng dụng

Ứng dụng là trang web tĩnh, không cần cài đặt máy chủ backend.

1. Tải hoặc clone repository.
2. Mở `index.html` bằng trình duyệt hiện đại.
3. Có thể triển khai toàn bộ repository lên GitHub Pages hoặc dịch vụ hosting tĩnh tương đương.

### Chạy bằng GitHub Pages
1. Đưa `index.html` và `README.md` lên repository GitHub.
2. Mở **Settings → Pages**.
3. Chọn nhánh triển khai (ví dụ `main`) và thư mục gốc `/`.
4. Lưu cấu hình, sau đó mở URL GitHub Pages được GitHub cung cấp.

## 💾 Lưu trữ dữ liệu và giới hạn

- Hồ sơ linh hồn, công hội và nhật ký được lưu trong `localStorage` của trình duyệt/thiết bị.
- Dữ liệu không tự đồng bộ giữa các thiết bị hoặc giữa nhiều người dùng.
- Dùng chức năng **Sao lưu dữ liệu JSON** trong ứng dụng để lưu hồ sơ và chuyển dữ liệu thủ công.
- Dữ liệu nhiệm vụ/công trạng của Công Hội được lưu riêng trên trình duyệt hiện tại.
- Đây là trò chơi/mô phỏng giải trí. Nghiệp lực, tội danh, hình phạt và phán quyết không phải kết luận pháp lý hay đánh giá con người thực tế.

## 🧰 Công nghệ

- HTML5
- CSS3
- JavaScript thuần
- Tailwind CSS qua CDN
- Google Fonts (Cinzel, JetBrains Mono, Space Grotesk)
- Trình duyệt hỗ trợ `localStorage`, `Blob` và JavaScript hiện đại

## 📦 Cấu trúc dự án

```text
.
├── index.html    # Ứng dụng UNDERWORLD OS 9.0
└── README.md     # Tài liệu dự án
```

## 📝 Phiên bản

- **9.0** – Bổ sung Công Hội Quỷ Sứ & Linh Hồn Lập Công, bảng nhiệm vụ truy bắt, phần thưởng công trạng, lịch sử áp giải và lộ trình thăng cấp/phong quan.
- **8.0** – Trung tâm điều hành, Tòa án Diêm Vương AI, Sổ Sinh Tử, bản đồ 18 tầng, công đức/đầu thai và nhật ký hệ thống.

---

**UNDERWORLD OS 9.0** · Mô phỏng quản lý Âm Phủ · 2026
