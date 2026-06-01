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
| Email | admin@gmail.com |
| Password | 123456 |

### User

| Thông tin | Giá trị |
|------------|----------|
| Email | user@gmail.com |
| Password | 123456 |

---

## 🖼 Hình ảnh minh họa

### Trang chủ

<p align="center">
 <img width="3029" height="1665" alt="image" src="https://github.com/user-attachments/assets/2c620561-cefd-46ed-b774-4759a637b6d7" />

</p>


## Trang chọn suất chiếu, rạp User
<img width="3016" height="1662" alt="image" src="https://github.com/user-attachments/assets/f1348fe9-143b-4408-af3b-e2b380407013" />

## Trang chọn ghế User
<img width="3064" height="1660" alt="image" src="https://github.com/user-attachments/assets/2cafd7ea-acbe-4b82-ab60-03acabdd0242" />

## Lịch sử đặt vé
<img width="3060" height="1657" alt="image" src="https://github.com/user-attachments/assets/8b7e5ec7-5e96-4eaa-a400-2b51e76261de" />

## Dashboard Admin
<img width="3010" height="1651" alt="image" src="https://github.com/user-attachments/assets/732a73f9-15af-4486-9584-0980d4b691c7" />

## Quản lí phim Admin
<img width="3013" height="1649" alt="image" src="https://github.com/user-attachments/assets/b676bcbe-0aea-47a0-9b6a-44599e0a4cf4" />

## Quản lí suất chiếu Admin
<img width="3017" height="1653" alt="image" src="https://github.com/user-attachments/assets/211b24a6-0471-45e7-a3e9-c15b81b72d45" />

## Quản lí người dùng Admin
<img width="3030" height="1741" alt="image" src="https://github.com/user-attachments/assets/9781d881-8814-464d-8a13-184f53503535" />


## 🎥 Video Demo

(https://drive.google.com/drive/folders/1zpdH9uJjjABv7kcfDaFtAc3brYajUt16?usp=sharing)

---

## 🌐 Website Deploy

**Website:** http://duyanh.name.vn

---

