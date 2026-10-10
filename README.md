# [Bài tập] Tạo Landing Page với Bootstrap và Hình Ảnh

Dự án bài tập thực hành thiết kế giao diện **Landing Page** chuyên nghiệp, hiện đại và chuẩn **Responsive** bằng cách kết hợp **Bootstrap Containers**, **Grid System**, **Buttons** và **Images (`img-fluid`)**.

---

## 🎯 Mục Tiêu Bài Tập

- Luyện tập sử dụng **Bootstrap Containers** (`container`, `container-fluid`) để bố trí các phân vùng nội dung chuẩn lề.
- Áp dụng thành thạo **Bootstrap Grid System** (`row`, `col-*`) để sắp xếp bố cục linh hoạt trên các kích thước màn hình.
- Sử dụng **Bootstrap Images** (đặc biệt là lớp `img-fluid`, `rounded-4`, `shadow-lg`) giúp hình ảnh hiển thị tự động co giãn, sắc nét trên mọi thiết bị.
- Sử dụng **Bootstrap Buttons** (`btn`, `btn-primary`, `btn-lg`, `btn-outline-*`) để tạo các nút Kêu Gọi Hành Động (CTA) nổi bật.
- Xây dựng theo phiên bản **Bootstrap 5.3**: Thay thế component Jumbotron đã bị loại bỏ bằng Hero Section tự tạo sử dụng các tiện ích `py-5`, `align-items-center`, `display-*` và CSS gradient hiện đại.

---

## 🏗️ Bố Cục Trang Web (Landing Page Architecture)

Trang web được tổ chức theo cấu trúc tiêu chuẩn:

```plaintext
Landing Page (NovaTech Cloud)
│
├── 1. Navbar: Thanh điều hướng thương hiệu và liên kết nhanh
│
├── 2. Banner / Hero Section:
│   ├── Tiêu đề & phụ đề nổi bật (Display Heading, Lead text)
│   ├── Nút CTA ("Trải nghiệm miễn phí", "Tìm hiểu thêm")
│   ├── Chỉ số thống kê (99.99% Uptime, 50k+ Khách hàng)
│   └── Hình ảnh Banner nổi bật (Sử dụng img-fluid & shadow-lg)
│
├── 3. Giới thiệu (About Section):
│   ├── Hình ảnh thực tế của đội ngũ / sản phẩm (img-fluid rounded-4)
│   └── Nội dung giới thiệu sản phẩm & danh sách lợi ích (Checkmarks)
│
├── 4. Danh sách tính năng (Features Grid - 4 Cột):
│   ├── Tính năng 1: Tốc độ vượt trội (NVMe + CDN)
│   ├── Tính năng 2: Bảo mật đa tầng (AES-256 & WAF)
│   ├── Tính năng 3: Tích hợp AI Trí tuệ (Dự báo tự động)
│   └── Tính năng 4: Hỗ trợ 24/7/365 (Phản hồi < 5 phút)
│
├── 5. Bộ sưu tập hình ảnh thực tế (Showcase):
│   └── Grid 3 cột hình ảnh minh họa đa thiết bị với img-fluid
│
├── 6. Kêu gọi hành động (CTA Banner):
│   ├── Tiêu đề thu hút & thông điệp ưu đãi 14 ngày dùng thử
│   ├── Nút hành động nổi bật ("Đăng ký ngay" mở Modal)
│   └── Nút "Xem thêm chi tiết"
│
└── 7. Footer & Modal Đăng ký:
    └── Bản quyền, liên kết mạng xã hội & form đăng ký nhanh
```

---

## 💡 Các Lớp Bootstrap Nổi Bật Được Áp Dụng

| Nhóm chức năng | Lớp Bootstrap sử dụng | Mục đích |
| :--- | :--- | :--- |
| **Containers** | `.container`, `.container-fluid` | Giới hạn chiều rộng và căn giữa bố cục |
| **Grid System** | `.row`, `.col-12`, `.col-sm-6`, `.col-lg-6`, `.col-lg-3`, `.g-4`, `.g-5` | Phân chia cột responsive từ mobile đến desktop |
| **Images** | `.img-fluid`, `.rounded-4`, `.rounded`, `.shadow-lg` | Giúp ảnh tự co giãn 100% chiều rộng cột, bo góc thẩm mỹ |
| **Buttons** | `.btn`, `.btn-primary`, `.btn-lg`, `.btn-outline-primary`, `.btn-light` | Tạo các nút CTA nổi bật với kích thước lớn và hiệu ứng hover |
| **Typography & Flex** | `.display-4`, `.display-6`, `.lead`, `.d-flex`, `.align-items-center` | Tăng tính phân cấp trực quan và căn chỉnh vị trí |

---

## 📱 Khả Năng Tương Thích & Responsive

- **Mobile (< 576px)**: Các cột tự động xếp chồng (stacking), ảnh tự co dãn vừa khít màn hình, các nút CTA dàn đều dọc để dễ chạm.
- **Tablet (768px - 991px)**: Lưới tính năng hiển thị 2 cột x 2 hàng cân đối.
- **Desktop (≥ 992px)**: Banner chia 2 cột đối xứng, danh sách tính năng trải đều 4 cột trên 1 hàng ngang.

---

## 🚀 Hướng Dẫn Xem Bài Thực Hành

1. **Xem trực tiếp bằng Trình duyệt**:
   - Nhấp đúp vào tệp [index.html](file:///d:/BaiTapGithub/index.html).
2. **Xem qua Live Server (VS Code / Antigravity IDE)**:
   - Chuột phải vào `index.html` chọn **Open with Live Server**.
   - Truy cập: `http://127.0.0.1:5500/index.html`.

---

## 👨‍💻 Thông Tin Tác Giả

- **Học viên**: dtc245200059
- **Email**: dtc245200059@ictu.edu.vn
- **Bài tập**: Tạo Landing Page với Bootstrap và Hình Ảnh
