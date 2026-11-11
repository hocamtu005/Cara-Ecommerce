# 🛍️ Cara Ecommerce v1.0

Đây là dự án website thương mại điện tử fullstack dành cho các shop thời trang và phụ kiện. Hệ thống được chia làm hai phần chính: một trang web để khách hàng vào mua sắm, chốt đơn và một trang quản trị riêng để Admin quản lý toàn bộ dữ liệu.

---

## ✨ Tính năng chính

### Khách hàng
- Xem danh sách sản phẩm, chi tiết sản phẩm, bài viết blog.
- Đăng ký, đăng nhập và quản lý thông tin tài khoản.
- Giỏ hàng linh hoạt, tiến hành đặt hàng và checkout.
- Theo dõi trạng thái đơn hàng.

### Quản trị viên
- Quản lý sản phẩm (thêm, sửa, xóa, danh mục).
- Quản lý đơn hàng và trạng thái xử lý.
- Quản lý thông tin khách hàng.

---

## 🛠️ Công nghệ sử dụng

- **Backend:** Native PHP
- **Database:** MySQL 8.0
- **Frontend:** HTML5, CSS3, JavaScript (Vanilla JS)
- **DevOps:** Docker, Docker Compose

---

## 📂 Cấu trúc thư mục

```text
cara-ecommerce/
├── admin/       # Giao diện và logic xử lý trang quản trị.
├── config/      # Cấu hình kết nối cơ sở dữ liệu.
├── core/        # Logic hệ thống (xác thực, giỏ hàng, hàm chung).
├── database/    # Script khởi tạo cơ sở dữ liệu.
├── includes/    # Thành phần giao diện dùng chung (header, footer).
└── public/      # Giao diện khách hàng và tài nguyên tĩnh (assets).
```

---

## 🚀 Hướng dẫn Cài đặt & Khởi chạy

### 1. Yêu cầu
- Cài đặt và chạy **Docker Desktop** trên máy.
- Cài đặt **Git** trên máy.

### 2. Các bước thực hiện

**Bước 1: Clone dự án và di chuyển vào thư mục**
```bash
git clone <repository-url>
cd cara-ecommerce
```

**Bước 2: Khởi chạy môi trường bằng Docker Compose**
```bash
docker compose up -d
```

### 3. Truy cập
- **Trang Cửa hàng:** [http://localhost:8082/public/index.php](http://localhost:8082/public/index.php)
- **Trang Quản trị:** [http://localhost:8082/admin/index.php](http://localhost:8082/admin/index.php)

### 4. Cổng kết nối
- **MySQL Host:** `127.0.0.1` (hoặc `localhost`)
- **MySQL Port:** `3308`