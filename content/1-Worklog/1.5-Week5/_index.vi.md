---
title: "Worklog Tuần 5"
date: 2026-04-27
weight: 1
chapter: false
pre: " <b> 1.5. </b> "
---


### Mục tiêu tuần 5:

* Tích hợp Amazon RDS vào ứng dụng PHP 
* Thực hiện các điều chỉnh cơ bản để đảm bảo kết nối database ổn định

### Các công việc cần triển khai trong tuần này:
| Thứ | Công việc                                                                                                                                                                                   | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu                            |
| --- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------ | --------------- | ----------------------------------------- |
| 2   | - Tạo RDS MySQL instance <br> - Cấu hình tên DB, user, password <br> - Bật public access để test                                                                                             | 06/04/2026   | 06/04/2026      |
| 3   | - Cấu hình Security Group mở port 3306 <br> - Cho phép EC2 truy cập RDS                                            | 07/04/2026   | 07/04/2026      | <https://cloudjourney.awsstudygroup.com/> |
| 4   | - Export database từ local <br> - Import vào RDS | 08/04/2026   | 08/04/2026      | <https://cloudjourney.awsstudygroup.com/> |
| 5   | - Sửa file config PHP (host, user, password) <br> - Thay localhost bằng endpoint RDS                  | 09/04/2026   | 09/04/2026      | <https://cloudjourney.awsstudygroup.com/> |
| 6   | - Test CRUD trên hệ thống <br> - Sửa lỗi timeout kết nối <br> - Kiểm tra log lỗi                                                                                         | 10/04/2026   | 10/04/2026      | <https://cloudjourney.awsstudygroup.com/> |


### Kết quả đạt được tuần 5:

* Tích hợp thành công cơ sở dữ liệu Amazon RDS vào ứng dụng PHP đang chạy trên Amazon EC2.
* Thiết lập kết nối ổn định giữa EC2 và RDS thông qua endpoint và cấu hình Security Group phù hợp.
* Import dữ liệu từ database local lên RDS và kiểm tra truy vấn hoạt động chính xác.
* Điều chỉnh cấu hình kết nối trong source code PHP (hostname, port, username, password, charset).
Xử lý các lỗi thường gặp như MySQL version, charset và driver kết nối (php-mysqlnd).
* Xây dựng file test kết nối database để kiểm tra và debug hệ thống.
* Đảm bảo ứng dụng có thể truy xuất và hiển thị dữ liệu động từ RDS một cách ổn định.
* Nắm được quy trình tích hợp database cloud vào ứng dụng web thực tế.


