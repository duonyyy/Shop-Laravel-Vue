<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400" alt="Laravel Logo"></a></p>

# 🛍️ shop-laravel-vue

Một ứng dụng e-commerce sử dụng Laravel làm backend API và Vue.js làm frontend.

## 📌 Yêu cầu hệ thống

- PHP >= 8.1
- Composer
- Node.js >= 16.x
- MySQL 
- Laravel >= 10.x
- Vue.js >= 3.x


## 🚀 Cài đặt và Chạy Dự Án

### 1️⃣ Clone dự án

git clone your-repo-url
cd project_name


2️⃣ Cấu hình môi trường
sh
Sao chép
Chỉnh sửa
cp .env.example .env
Chỉnh sửa file .env và thiết lập thông tin database:

env
Sao chép
Chỉnh sửa
DB_DATABASE=your_database
DB_USERNAME=your_user
DB_PASSWORD=your_password
Tạo application key:

sh
Sao chép
Chỉnh sửa
php artisan key:generate
3️⃣ Cài đặt dependencies
sh
Sao chép
Chỉnh sửa
composer install
npm install
4️⃣ Chạy migration và seed dữ liệu (nếu có)
sh
Sao chép
Chỉnh sửa
php artisan migrate --seed
5️⃣ Khởi chạy server Laravel
sh
Sao chép
Chỉnh sửa
php artisan serve
6️⃣ Chạy Vue.js frontend
Nếu dùng Vite:
sh
Sao chép
Chỉnh sửa
npm run dev
Nếu dùng Webpack:
sh
Sao chép
Chỉnh sửa
npm run watch
🔗 API Endpoints
Phương thức	Đường dẫn	Mô tả
GET	/api/categories	Lấy danh mục
GET	/api/products	Lấy danh sách sản phẩm
POST	/api/orders	Tạo đơn hàng
🎨 Công nghệ sử dụng
Backend: Laravel 10, MySQL
Frontend: Vue.js 3, Tailwind CSS
API Authentication: Sanctum
Thanh toán: VNPAY (nếu có)
