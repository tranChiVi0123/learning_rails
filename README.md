# ruby_on_rails_basic

## Chương_1 Xây dựng cài đặt ban đầu 
1. Tạo một project mới sau khi cài đặt xong rails  
    > rails new Project  
2. Bật server  
    > rails server  
    or  
    > rails s  
3. *fix lỗi đầu tiên ( lỗi phiên bản được lỗi trong **Gemfile**)*  
    > Gemfile được tạo thông qua bundle:  **bundle install**
4. Mô hình MVC trong rails:  
  _Các tiêu chuẩn Rails ứng dụng cấu trúc có một thư mục ứng dụng được gọi app/, trong đó bao gồm các thư mục con gọi **models**, **views**và **controllers**.Đây là một gợi ý rằng Rails tuân theo mẫu kiến trúc mô hình (MVC), thực thi một sự tách biệt giữa dữ liệu trong ứng dụng (như thông tin người dùng) và mã được sử dụng để hiển thị nó, đây là cách cấu trúc phổ biến giao diện người dùng đồ họa (GUI)._  

5. Hello world!  
   Trong thư mục *app/controllers/application_controller.rb*  
   > class ApplicationController < ActionController::Base  
   > protect_from_forgery with: :exception  
   > def hello  
   >    render html: "hello, world!"  
   > end  
   >end
     
   Mở router trong *config/routes.rb*  
   > root 'application#hello'  
 6. Làm việc với git:  
    **Tham khảo thêm tại:** http://rogerdudler.github.io/git-guide/index.vi.html  
 7. Heroku  
      *Heroku là một nền tảng được lưu trữ được xây dựng dành riêng cho việc triển khai Rails và các ứng dụng web khác. Heroku làm cho việc triển khai các ứng dụng Rails dễ dàng một cách lố bịch miễn là mã nguồn của bạn nằm dưới sự kiểm soát phiên bản với Git.*  

___  
      
## Chương_2  Một app đơn giản sơ bộ về sự hoạt đông của mô hình MVC
  
___  
## Chương_3 Các trang tĩnh  
    1. Sử dụng markdown để viết README.ME  
      https://gsviec.com/blog/huong-dan-su-dung-markdown  
      
    

