# config_PHP_laravel

# LƯU Ý: php artisan serve

# Lưu ý: điều kiện phải cần 

- Xampp
- Composer
# Thứ nhất:
- 1: cd C:\xampp\htdocs

- 2: cd C:\xampp\htdocs\composer create-project laravel/laravel tên_thư_mục
# Thứ 2: 
- Sau khi tạo thành công: 
   +  1> localhost/muc/public  
    +  2> 127.0.0.1/...
          
# Thứ 3: 
 *vào resource/view -> tạo thêm 1 home.blade.php 
=> gõ các lệnh html vào
 * vào route/web.php 
=> route::get ('/', function (){
   return view ('welcome');
   });
