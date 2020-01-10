# SE03-Group-08
Tên đề tài: Thiết kế web nghe nhạc 
Sản phẩm là web âm nhạc như Zingmp3 có chức năng nghe nhạc, tải bài hát...ở bất cứ đâu.

1.1.Định hướng
- Học cách làm việc nhóm
- Học cách sử dụng github, khám phá các chức năng cũng như công cụ của github...
- Học cách hiểu ý các thành viên trong nhóm, tạo mỗi liên kết giữa các thành viên để tạo ra sản phẩm một cách hiệu quả, sáng tạo.
- Biết cách tạo ra 1 project cần những giai đoạn nào, giai đoạn nào là quan trọng và cần thiết nhất.
- Nâng cao kỹ năng xây dựng và phát triển 1 trang web.
- Tạo 1 trang web tốt để thi vấn đáp cuối kỳ môn công nghệ phần mềm.


1.2.Các kết quả then chốt
- Thiết kế được web âm nhạc tương tự như web Zingmp3.com
- Nếu thành công và có nhiều ý tưởng tốt, sẽ tạo thành web hoàn chỉnh có nhiều chức năng hơn.



1.3.Công nghệ và Công cụ
- Sử dụng wordpress là chính
- Các ngôn ngữ hỗ trợ như html, css, php làm giao diện...
- Database:Mysql



1.4.Đối tượng người dùng
- Tất cả mọi người: có thể nghe và tải nhạc
- Admin: quản lí và tải nhạc lên web

1.5. Mục tiêu, thời hạn hoàn thành
- Mục tiêu Hoàn thành sản phẩm trước deadline ít nhất 1 tuần. Sau đó tiến hành chạy thử nghiệm
1.6 Hướng dẫn cài đặt và sử dụng
-Chuẩn bị Hosting (có Cpanel)
  Đầu tiên là bạn cần chuẩn bị một hosting có Cpanel.
  Thường các shared host hiện nay đều sử dụng Cpanel hoặc AdminDirect.
  Bạn cần có một cơ sở dữ liệu chuẩn như MySQL
  Có sẵn một tên miền
- Cài đặt Wordpress
-Bước #1: Upload file wordpress.zip lên server
   - Đầu tiên chúng ta tải về phiên bản mới nhất của WordPress từ WordPress.org.
   Upload file zip bạn vừa tải về lên server:
   - Sử dụng File Manage (Cpanel) để upload file zip
   Đăng nhập tài khoản hosting mà bạn được cung cấp.
   Nhấp chuột vào cPanel File Manager để mở
   Nếu một thông báo ở đây hãy chọn Web Root.
   Truy cập vào thư mục public_html. Click Upload
   Chọn file wordpress.zip đã tải từ trước
   Sau khi upload xong, đóng tab và trở về File Manager.
   Nếu bạn vẫn không thấy một tập tin nào trong thư mục, bấm nút Reload (và không phải nút F5 của trình duyệt). Bạn sẽ thấy file                wordpress.zip bây giờ.
   Giải nén file wordpress.zip,bây giờ bạn sẽ thấy toàn bộ soure code WordPress đã sẵn sàng để cài đặt
-Bước #2: Tạo database và database user
  -Tạo database trong cPanel, Trong phần DATABASES, chọn MySQL Database Wizard,Đặt tên cho Database mới
  -Bước tiếp theo là tạo database users. Tương tự chúng ta đặt tên và tạo mật khẩu
  -Kết nối Database và User
  -Ở bước này chúng ta sẽ kết nối database và database user vừa tạo với nhau.
  -Ngoài ra bạn sẽ còn phải cấp quyền cho user này nữa.
  -Nếu bạn không quan tâm đến mấy cái này thì tốt nhất là:
  -Tích vào ALL PRIVILEGES 
  -Chọn Next Step
-Bước #3: Chạy WordPress Setup
  -Bạn đã có đầy đủ mọi thứ giờ chúng ta sẽ chạy cài đặt WordPress ( five minute WordPress installation).
  -Đi đến đường dẫn, để khởi động quá trình cài đặt.
    -Chọn ngôn ngữ rồi Continue, bạn cần một số thông tin cần chuẩn bị.
        -Database name
        -Database username
        -Database password
        -Database host
        -Table prefix
      -Bấm Let’s go!
      -Điền các thông tin đã tạo ở Bước #1 và Bước #2
          -Database Host: sẽ là localhost
          -Table Prefix: bạn có thể đặt wp_ (nên đổi sang cái khác)
          -Nhớ kiểm tra chính xác rồi bấm Submit
      -Click Run the installation
      -Bạn sẽ cần điền thêm một số thông tin cơ bản cho website:
            -Site Title, Username, Email
            -Tích vào “Discourage search engines from indexing this site”
            -Nếu bạn không muốn website này được index.
            -Cuối cùng là bấm Install WordPress.
-Xong ! Chúng ta đã thành công cài đặt wordpress thủ công 100%. Và hãy làm trang web của mình trở nên hoàn hảo nhé! 
