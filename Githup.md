Làm quen với git
==============
 # Giới thiệu #

Git là hệ thống quản lý các version trong quá trình phát triển phần mền,để dễ hiểu và không dài dòng.
Khi sử dụng git tức là bạn đang viết phần mềm trong kho lưu trữ, các bản version được cập nhật sau mỗi lần commit.
Git giúp lập trình viên quản lý sự thay đổi của code mà họ viết , bạn không lo bị mất  hay hỏng code ,
bởi vì mọi sự thay đổi sau mỗi lần bạn commit sẽ được lưu lại chi tiết trong file log. Ngoài ra bạn có thể lưu trữ code
online trực tiếp trên github.com, và tất nhiên là miễn phí, bạn muốn lưu riêng tư không ai nhìn thấy thì mới phải trả phí.

# Cài đặt git. #

Ở đây mình hướng dẫn các bạn cài và sử dụng git trên windown và linux ,

## Trên môi trường linux, mở terminal và gỡ # 

    Debian như Ubuntu
    $ apt-get update
    $ apt-get install git
    Fedora, 
    $ yum install git-core
    
## Cài đặt Git trên Windows rất đơn giản ## 
Tải về tập tin cài đặt định dạng exe từ Github, và chạy: http://msysgit.github.com/
# Lệnh cơ bản
 ### + Tạo 1 kho git để lưu trữ ###
 Di chuyển tới thư mục chứa dư án bạn đang thực hiện, mở terminal on linux hoặc trên win click chuột phải
 chọn "Git bash here"
  $ git init
  Thêm các file vào kho 
  $ git add . (Thêm mọi file có trong thư mục)
  hoặc 
  $ git add <tên file>
### + Lệnh commit (xác nhận sự thay đổi của dự án)  ###
  $ git commit -m 'tên commit'
### + Lưu trữ online ###
  Lệnh khai báo kho lưu trữ online trên gitub, bạn cần tạo 1 tài khoản trên github và tạo 1 kho ( new Repository)
  $ git remote add origin <url kho lưu trữ>
  Lệnh tải 1 dự án có sẵn trên githup
  $ git clone <url>
