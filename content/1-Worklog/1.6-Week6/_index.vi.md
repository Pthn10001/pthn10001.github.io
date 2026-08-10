---
title: "Worklog Tuần 6"
date: 2026-06-22
weight: 1
chapter: false
pre: " <b> 1.6. </b> "
---

### Mục tiêu tuần 6:

* Nắm vững mô hình Serverless trên AWS thông qua AWS Lambda và các dịch vụ liên quan.
* Hiểu và thực hành xây dựng Backend Serverless với AWS Lambda, Amazon S3 và Amazon DynamoDB.
* Thành thạo sử dụng AWS CLI để quản lý và tự động hóa các tài nguyên AWS.
* Tìm hiểu và triển khai Amazon ElastiCache nhằm tối ưu hiệu năng ứng dụng bằng cơ chế bộ nhớ đệm.
* Củng cố kỹ năng tự động hóa, quản lý hạ tầng và vận hành các dịch vụ AWS.

### Các công việc trong tuần 6:
| Thứ | Công việc                                                                                                                                                                                   | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu                            |
| --- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------ | --------------- | ----------------------------------------- |
| 2   | - **Thực hành Lab 13:** Serverless Automation (AWS Lambda) <br>&emsp; + Khởi tạo hạ tầng VPC và EC2 <br>&emsp; + Thiết lập Incoming Webhooks cho Slack <br>&emsp; + Khai báo IAM Role và gán Tag cho tài nguyên <br>&emsp; + Viết hàm Lambda để tự động Start/Stop EC2 instance và gửi thông báo qua Slack | 27/07/2026   | 27/07/2026      | [Lab 13 Tự động hóa bằng Serverless với AWS Lambda](https://000022.awsstudygroup.com/vi/) |
| 3   | - **Thực hành Lab 14:** Xây dựng Serverless Backend <br>&emsp; + Viết Lambda function xử lý ảnh tự động khi có file upload lên S3 bucket <br>&emsp; + Phân quyền IAM policy cho Lambda <br>&emsp; + Khởi tạo bảng DynamoDB và lập trình hàm Lambda để ghi dữ liệu log/thông tin vào DB | 28/07/2026   | 28/07/2026      | [Lab 14 Backend Serverless với Lambda, S3 và DynamoDB](https://000078.awsstudygroup.com/vi/) |
| 4   | - **Thực hành Lab 15 (Phần 1):** Làm quen với AWS CLI <br>&emsp; + Cài đặt và cấu hình AWS CLI trên máy cá nhân <br>&emsp; + Sử dụng command line để truy vấn thông tin tài nguyên <br>&emsp; + Tương tác với Amazon S3 và Amazon SNS thông qua giao diện dòng lệnh | 29/07/2026   | 29/07/2026      | [Lab 15 Thao tác dòng lệnh với AWS CLI](https://000011.awsstudygroup.com/vi/) |
| 5   | - **Thực hành Lab 15 (Phần 2):** <br>&emsp; + Quản lý tài khoản IAM bằng CLI <br>&emsp; + Cấu hình mạng VPC và Internet Gateway bằng các dòng lệnh <br>&emsp; + Khởi chạy máy chủ ảo EC2 không cần dùng AWS Console <br>&emsp; + Kỹ năng xử lý lỗi (Troubleshooting) cơ bản trên CLI | 30/07/2026   | 30/07/2026      | [Lab 15 Thao tác dòng lệnh với AWS CLI](https://000011.awsstudygroup.com/vi/) |
| 6   | - **Thực hành Lab 16:** Tối ưu hiệu năng với ElastiCache <br>&emsp; + Chuẩn bị Access Key và môi trường CLI <br>&emsp; + Thiết lập Subnet Group cho cache <br>&emsp; + Tạo cụm ElastiCache trong 2 chế độ: tắt và bật Cluster Mode | 31/07/2026   | 31/07/2026      | [Lab 16 Bộ nhớ đệm trong bộ nhớ với Amazon ElastiCache](https://000061.awsstudygroup.com/vi/) |


### Kết quả đạt được tuần 6:
* **Kiến trúc Serverless:** Phát triển thành công các hàm AWS Lambda để tự động hóa hạ tầng (Start/Stop EC2 theo lịch) và tích hợp cảnh báo thời gian thực về Slack.
* **Xây dựng Backend phi máy chủ:** Phối hợp nhịp nhàng giữa Amazon S3, AWS Lambda và DynamoDB để tạo ra một luồng xử lý ảnh tự động và lưu trữ metadata không cần quản lý máy chủ.
* **Thao tác dòng lệnh (AWS CLI):** Nâng cao kỹ năng quản trị hệ thống, làm quen với việc tương tác, cấu hình IAM, VPC, S3 và EC2 hoàn toàn thông qua giao diện dòng lệnh (CLI).
* **Tối ưu tốc độ ứng dụng:** Thực hành cấu hình cụm Amazon ElastiCache (ở cả hai chế độ bật/tắt Cluster Mode), hiểu rõ cơ chế cache trong bộ nhớ (In-memory caching).