##Setup
- Yêu cầu:
    - Cài đặt PHP 7.4
    - Cài đặt MySQL
    - Cài đặt Composer
- Chạy chương trình:
    - Bước 1: Tạo CSDL mới trên MySQL
    - Bước 2: Chạy câu lệnh `composer update` để cập nhật thư viện
    - Bước 3: Copy file `.env.example` ra 1 file đặt tên là `.env`
    - Bước 4: Thay đổi các config db trong file `.env`:
        - DB_DATABASE = < ten db >
        - DB_USERNAME = < ten tk mysql >
          DB_PASSWORD = <mật khẩu tk mysql>
    - Bước 5: Chạy câu lệnh `php artisan migrate --seed` để cập nhật Database;
    - Bước 6: Chạy câu lệnh `php artisan key:generate`
    - Bước 7: Khởi chạy dự án: `php artisan serve`
