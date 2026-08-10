---
title: "Worklog Tuần 8"
date: 2026-06-22
weight: 1
chapter: false
pre: " <b> 1.8. </b> "
---

### Mục tiêu tuần 8:

* Nắm vững cách xây dựng và quản lý hạ tầng bằng AWS Cloud Development Kit (AWS CDK).
* Hiểu và thực hành triển khai các ứng dụng trên AWS bằng Infrastructure as Code với CloudFormation và AWS CDK.
* Xây dựng và triển khai Backend Serverless sử dụng AWS Lambda, Amazon S3 và Amazon DynamoDB.
* Hiểu quy trình phát triển Frontend tích hợp với API Serverless thông qua API Gateway và Lambda.
* Củng cố kỹ năng triển khai và quản lý kiến trúc ứng dụng hiện đại trên AWS.

### Các công việc trong tuần 8:
| Thứ | Công việc                                                                                                                                                                                   | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu                            |
| --- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------ | --------------- | ----------------------------------------- |
| 2   | - **Thực hành Lab 19:** Làm quen với AWS CDK (Cloud Development Kit) <br>&emsp; + Chuẩn bị IAM Role và cấu hình môi trường code trên Cloud9 <br>&emsp; + Khởi tạo CDK Workspace, viết mã khai báo hạ tầng (CDK Template) <br>&emsp; + Triển khai (deploy) và cập nhật hạ tầng tự động <br>&emsp; + Dọn dẹp tài nguyên | 11/08/2025   | 11/08/2025      |[Lab 19 Bộ công cụ phát triển đám mây (AWS CDK) cơ bản](https://000038.awsstudygroup.com/vi/)|
| 3   | - **Thực hành Lab 20:** Kỹ thuật CDK Nâng cao <br>&emsp; + Setup môi trường lập trình VSCode cục bộ kết nối AWS <br>&emsp; + Viết code CDK để khởi tạo hệ thống Container (ECS, ALB, API Gateway) <br>&emsp; + Tích hợp Lambda xử lý sự kiện từ S3 <br>&emsp; + Quản lý các cấu phần phức tạp bằng Nested Stacks | 12/08/2025   | 12/08/2025      | [Lab 20 AWS CDK nâng cao](https://000076.awsstudygroup.com/vi/) |
| 4   | - **Thực hành Lab 21:** IaC Workshop <br>&emsp; + Tự động hóa quá trình tạo Lambda, VPC và EC2 <br>&emsp; + Dựng kiến trúc ứng dụng 3 lớp (Three-Tier Architecture) hoàn chỉnh thông qua CloudFormation Stack <br>&emsp; + Kiểm tra luồng truy cập độc lập ở từng tầng: Web, Application và Database | 13/08/2025   | 13/08/2025      | [Lab 21 Workshop Infrastructure as Code](https://000102.awsstudygroup.com/vi/) |
| 5   | - **Thực hành Lab 22:** Ôn tập Backend Serverless (Lambda, S3, DynamoDB) <br>&emsp; + Xây dựng luồng tự động resize ảnh khi có dữ liệu đẩy lên S3 <br>&emsp; + Gán quyền IAM Policy cho Lambda function <br>&emsp; + Viết logic ghi dữ liệu metadata của file ảnh vào bảng DynamoDB | 14/08/2025   | 14/08/2025      | [Lab 22 Backend Serverless với Lambda, S3 và DynamoDB](https://000078.awsstudygroup.com/vi/) |
| 6   | - **Thực hành Lab 23:** Tích hợp Frontend & API Serverless <br>&emsp; + Thiết kế bảng DynamoDB và logic API qua Lambda <br>&emsp; + M mở cổng giao tiếp với API Gateway (Tạo Methods, Bật CORS) <br>&emsp; + Thử nghiệm API độc lập bằng Postman <br>&emsp; + Tích hợp API vào mã nguồn Frontend và hoàn tất kiểm thử E2E (End-to-End) | 15/08/2025   | 15/08/2025      | [Lab 23 Phát triển Frontend cho API Serverless](https://000079.awsstudygroup.com/vi/) |


### Kết quả đạt được tuần 8:

* **Làm chủ AWS CDK:** Thành thạo phương pháp định nghĩa hạ tầng bằng mã lập trình quen thuộc (CDK). Triển khai dễ dàng các stack phức tạp chứa ECS, ALB và Nested Stacks thay vì viết JSON/YAML thuần túy.
* **Kiến trúc Đa tầng (Three-Tier):** Áp dụng IaC để dựng thành công một mô hình ứng dụng 3 lớp (Web, App, DB) kinh điển, kiểm soát luồng mạng độc lập và bảo mật cao.
* **Serverless Fullstack:** Đóng gói hoàn chỉnh dự án Serverless từ đầu đến cuối: Frontend tương tác với API Gateway, backend Lambda xử lý logic và lưu trữ dữ liệu an toàn trên DynamoDB.
* **Sẵn sàng báo cáo:** Tích lũy đủ kiến thức, kinh nghiệm thực chiến và hoàn thiện mô hình để tự tin bước vào vòng thuyết trình dự án (Capstone) cuối khóa.