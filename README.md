# 🎬 Website Đặt Vé Xem Phim Online

## 📖 Giới thiệu

Website Đặt Vé Xem Phim Online là hệ thống hỗ trợ người dùng tìm kiếm phim, xem lịch chiếu và đặt vé trực tuyến thông qua giao diện website.

Hệ thống được xây dựng nhằm mô phỏng quy trình hoạt động của một website đặt vé xem phim thực tế, giúp người dùng có thể:

- Đăng ký tài khoản
- Đăng nhập hệ thống
- Đăng nhập bằng Google
- Xem danh sách phim
- Xem chi tiết phim
- Xem lịch chiếu theo rạp
- Chọn ghế trực tuyến
- Đặt vé xem phim
- Theo dõi lịch sử đặt vé

Ngoài ra, hệ thống còn cung cấp trang quản trị dành cho Admin để quản lý:

- Phim
- Người dùng
- Suất chiếu
- Phòng chiếu
- Ghế ngồi
- Đơn đặt vé (Booking)
- Dashboard thống kê

---

## 👨‍💻 Thành viên thực hiện

| Họ và tên | MSSV | Vai trò |
|-----------|------|----------|
| Nguyễn Vũ Anh | 23810310237 | Leader / Frontend |
| Bùi Việt Hoàng | 23810310241 | Backend |
| Nguyễn Bá Duy Anh | 23810310238 | Database / Deploy |

---

## 📌 Phân công nhiệm vụ

| Thành viên | Nhiệm vụ |
|------------|-----------|
| Bùi Việt Hoàng | Xây dựng Backend bằng NestJS, phát triển REST API, xác thực người dùng bằng JWT và tích hợp Google Login |
| Nguyễn Vũ Anh | Thiết kế giao diện ReactJS, xây dựng các chức năng phía người dùng và tối ưu Responsive UI |
| Nguyễn Bá Duy Anh | Thiết kế cơ sở dữ liệu MySQL, triển khai VPS, cấu hình Docker, Redis, Nginx và quản trị hệ thống |

---

## 🛠 Công nghệ sử dụng

### Frontend

- ReactJS
- Vite
- Bootstrap
- Axios
- React Router DOM
- Socket.IO Client

### Backend

- NestJS
- TypeScript
- Prisma ORM
- JWT Authentication
- Passport Google OAuth

### Database

- MySQL

### Cache & Realtime

- Redis
- Socket.IO

### Deploy & Infrastructure

- Ubuntu VPS
- Docker
- Docker Compose
- Nginx

---

## 📂 Cài đặt dự án

### Clone Source Code

```bash
git clone https://github.com/DuyAnh231o/web_site_movie_booking_systerm.git
cd web_site_movie_booking_systerm
```

---

### Cài đặt Frontend

```bash
cd frontend
npm install
```

### Cài đặt Backend

```bash
cd backend
npm install
```

---

## ⚙️ Cấu hình môi trường Backend

Tạo file `.env` trong thư mục backend:

```env
DATABASE_URL=mysql://root:123456@mysql:3306/movie_booking

JWT_SECRET=your_secret_key

GOOGLE_CLIENT_ID=your_google_client_id
GOOGLE_CLIENT_SECRET=your_google_client_secret

GOOGLE_CALLBACK_URL=http://localhost:3000/api/auth/google/callback

REDIS_HOST=redis
REDIS_PORT=6379
```

---

## 🗄 Khởi tạo cơ sở dữ liệu

### Generate Prisma Client

```bash
npx prisma generate
```

### Đồng bộ Database

```bash
npx prisma db push
```

---

## 🚀 Chạy dự án

### Chạy bằng Docker

```bash
docker compose up -d --build
```

### Chạy Backend

```bash
npm run start:dev
```

### Chạy Frontend

```bash
npm run dev
```

---

## 🔑 Tài khoản Demo

### Admin

| Thông tin | Giá trị |
|------------|----------|
| Email | duyanhth5@gmail.com |
| Password | boimixi36 |

### User

| Thông tin | Giá trị |
|------------|----------|
| Email | worogo9175@okcdeals.com |
| Password | boimixi36 |

---

## 🖼 Hình ảnh minh họa

### Trang chủ

<p align="center">
  <img src="images/home.png" width="900">
</p>

### Chi tiết phim

<p align="center">
  <img src="images/movie-detail.png" width="900">
</p>

### Chọn suất chiếu

<p align="center">
  <img src="images/showtime.png" width="900">
</p>

### Chọn ghế

<p align="center">
  <img src="images/seat-booking.png" width="900">
</p>

### Lịch sử đặt vé

<p align="center">
  <img src="images/history.png" width="900">
</p>

### Trang quản trị

<p align="center">
  <img src="images/admin-dashboard.png" width="900">
</p>

---

## 🎥 Video Demo

> Đang cập nhật...

---

## 🌐 Website Deploy

**Website:** http://duyanh.name.vn

---

## 📄 Giấy phép

Dự án được phát triển phục vụ mục đích học tập và nghiên cứu tại trường đại học.
