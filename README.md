# SmartCampus - Ứng dụng Di động Hỗ trợ Sinh viên

Ứng dụng di động thông minh giúp sinh viên **PTIT** dễ dàng **tra cứu lịch học**, tìm kiếm phòng học trống và cập nhật nhanh chóng các thông báo mới nhất từ nhà trường.

- Các tính năng chính của hệ thống:
  - Tra cứu lịch học theo mã sinh viên[cite: 1].
  - Xem danh sách phòng học trống theo tòa nhà[cite: 1].
    - Cập nhật theo thời gian thực (Real-time)[cite: 1].
    - Hỗ trợ lọc theo trạng thái phòng[cite: 1].

[Trang chủ CLB Lập trình PTIT](https://clblaptrinh.ptit.edu.vn)[cite: 1]

![Logo SmartCampus](https://images.unsplash.com/photo-1517694712202-14dd9538aa97)[cite: 1]

> **Cảnh báo:** Dự án hiện đang trong giai đoạn phát triển thử nghiệm, chưa được sử dụng chính thức cho các hoạt động hành chính của trường[cite: 1].

---

## Phần Kỹ Thuật Dự Án

### Lệnh Cài Đặt Dự Án
```bash
git clone [https://github.com/clb-lap-trinh/smartcampus.git](https://github.com/clb-lap-trinh/smartcampus.git)
npm install
npm start
```[cite: 1

### Trạng Thái Công Việc (Task List)
- [x] Tra cứu lịch học theo mã sinh viên[cite: 1]
- [x] Xem danh sách phòng trống theo tòa nhà[cite: 1]
- [ ] Thông báo đẩy (push notification)[cite: 1]
- [ ] Đăng nhập bằng tài khoản trường[cite: 1]

### Bảng Thư Viện Sử Dụng

| Thư viện | Phiên bản | Mục đích |
| :--- | :---: | --- |
| React Native | 0.74 | Xây giao diện đa nền tảng iOS/Android |
| Axios | 1.6 | Gọi API lấy dữ liệu lịch học |[cite: 1]

### Ghi Chú Kỹ Thuật (Escape Characters)
Để hiển thị nguyên văn các ký tự đặc biệt trong tài liệu Markdown như dấu thăng hoặc dấu sao, chúng ta sử dụng dấu gạch chéo ngược ở phía trước (ví dụ: viết `\#` hoặc `\*`)[cite: 1].

---

## Ghi Chú Ôn Tập & Phân Tích Bẫy Cú Pháp (Phần 4)

### 1. Chỉ ra chính xác 2 lỗi cú pháp trong đoạn mã mẫu[cite: 1]:
- **Lỗi ở Bảng (Table):** Đoạn mẫu bị thiếu hoàn toàn dòng phân cách `| --- | --- |` nằm ngay phía dưới dòng tiêu đề cột, khiến hệ thống không nhận diện được bảng[cite: 1].
- **Lỗi ở Danh sách công việc (Task List):** Các mục danh sách `- [x]` và `- [ ]` bị thiếu khoảng trắng (space) giữa dấu gạch ngang và cặp ngoặc vuông, khiến hộp kiểm tương tác không hiển thị[cite: 1].

### 2. Đoạn mã đã được sửa đúng chuẩn[cite: 1]:
```markdown
| Tính năng | Trạng thái |
| :--- | :--- |
| Tra cứu lịch học | Xong |
| Push notification | Đang làm |

- [x] Tra cứu lịch học
- [ ] Push notification
```[cite: 1]