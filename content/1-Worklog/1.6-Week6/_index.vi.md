---
title: "Worklog Tuần 6"
date: 2026-04-27
weight: 1
chapter: false
pre: " <b> 1.6. </b> "
---


### Mục tiêu tuần 6:

* Tập trung tích hợp Amazon S3 vào ứng dụng PHP để quản lý và lưu trữ các file tĩnh như hình ảnh. 
* Tăng khả năng mở rộng và giảm tải lưu trữ cho EC2.

### Các công việc cần triển khai trong tuần này:
| Thứ | Công việc                                                                                                                                                                                   | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu                            |
| --- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------ | --------------- | ----------------------------------------- |
| 2   | - Tạo S3 bucket <br> - Chọn region và đặt tên phù hợp <br> - Kiểm tra cáu hình bucket                                                                                              | 13/04/2026   | 13/04/2026      |
| 3   | - Cấu hình bucket policy cho phép truy cập public <br> - Kiểm tra quyền IAM                                            | 14/04/2026   | 14/04/2026      | <https://cloudjourney.awsstudygroup.com/> |
| 4   | - Cài AWS SDK cho PHP <br> - Cấu hình Access Key và Secret Key | 15/04/2026   | 15/04/2026      | <https://cloudjourney.awsstudygroup.com/> |
| 5   | - Viết chức năng upload fiel từ PHP lên S3 <br> - Test upload hình ảnh                  | 16/04/2026   | 16/04/2026      | <https://cloudjourney.awsstudygroup.com/> |
| 6   | - Lấy URL file S3 <br> - Hiển thị hình ảnh trên website <br> - Kiểm tra tốc độ tải                                                                                         | 15/08/2025   | 15/08/2025      | <https://cloudjourney.awsstudygroup.com/> |


### Kết quả đạt được tuần 6:

* Tích hợp thành công Amazon S3 vào ứng dụng PHP để lưu trữ file tĩnh (hình ảnh, media).
* Thực hiện upload file từ ứng dụng lên S3 và nhận về URL để sử dụng trong hệ thống.
* Cấu hình bucket, phân quyền truy cập (public read) và quản lý file trên S3.
* Điều chỉnh source code để lưu URL file thay vì lưu trực tiếp trên server.
* Hiển thị dữ liệu hình ảnh trực tiếp từ S3 trên giao diện web.
* Giảm tải cho server Amazon EC2, cải thiện hiệu năng hệ thống.
* Tăng khả năng mở rộng và độ ổn định khi xử lý tài nguyên tĩnh.
* Hiểu rõ mô hình tách biệt giữa application server và storage trong kiến trúc cloud.


