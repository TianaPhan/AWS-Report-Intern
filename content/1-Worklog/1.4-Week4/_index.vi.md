---
title: "Worklog Tuần 4"
date: 2026-04-27
weight: 1
chapter: false
pre: " <b> 1.4. </b> "
---


### Mục tiêu tuần 4:

* Tập trung triển khai ứng dụng web PHP có sẵn lên EC2 và đưa hệ thống hoạt động online.
* Hiểu quy trình deploy và cấu hình web server trong môi trường cloud.

### Các công việc cần triển khai trong tuần này:
| Thứ | Công việc                                                                                                                                                                                   | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu                            |
| --- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------ | --------------- | ----------------------------------------- |
| 2   | - Upload mã nguồn PHP lên EC2 bằng WinSCP <br> - Kiểm tra cấu trúc file sau khi upload                                                                                             | 30/03/2026   | 30/03/2026      |
| 3   | - Di chuyển mã nguồn vào thư mục /var/www/html <br> - Kiểm tra cấu hình web root của Apache                                            | 31/03/2026   | 31/03/2026      | <https://cloudjourney.awsstudygroup.com/> |
| 4   | - Cấu hình quyền truy cập bằng chmod, chown <br> - Đảm bảo Apache có quyền truy cập file | 01/04/2026   | 01/04/2026      | <https://cloudjourney.awsstudygroup.com/> |
| 5   | - Khởi động lại Apache <br> - Truy cập web bằng IP public của EC2 <br> - Kiểm tra giao diện và chức năng cơ bản                 | 02/04/2026   | 02/04/2026      | <https://cloudjourney.awsstudygroup.com/> |
| 6   | - Phát hiện và sửa các lỗi trong ứng dụng <br> - Test lại hệ thống                                                                                         | 03/04/2026   | 03/04/2026      | <https://cloudjourney.awsstudygroup.com/> |


### Kết quả đạt được tuần 4:

* Triển khai thành công ứng dụng web PHP lên Amazon EC2 và đưa hệ thống hoạt động online thông qua Public IP.
* Cấu hình hoàn chỉnh môi trường web server (Apache, PHP) trên EC2, đảm bảo ứng dụng chạy ổn định.
* Upload source code từ local lên server bằng SCP và deploy vào thư mục /var/www/html.
* Thiết lập quyền truy cập file phù hợp và xử lý các lỗi liên quan đến permission.
* Kiểm tra và xác nhận website có thể truy cập từ trình duyệt bên ngoài.
* Hiểu rõ quy trình deploy ứng dụng từ môi trường local lên server cloud.
* Tích lũy kinh nghiệm thực tế trong việc đưa một ứng dụng web vào môi trường vận hành thực tế.


