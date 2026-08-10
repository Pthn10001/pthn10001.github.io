---
title: "Worklog Tuần 5"
date: 2026-06-22
weight: 1
chapter: false
pre: " <b> 1.5. </b> "
---

### Mục tiêu tuần 5:

* Nắm vững kiến thức cơ bản về các dịch vụ cơ sở dữ liệu AWS như Amazon RDS, Aurora, Redshift và ElastiCache.
* Hiểu và thực hành triển khai Static Website với Amazon S3 và tăng tốc truy cập bằng CloudFront.
* Thực hành các thao tác cơ bản với Amazon RDS, bao gồm khởi tạo database, triển khai ứng dụng, backup và restore.
* Hiểu và triển khai EC2 Auto Scaling kết hợp với Load Balancer để mở rộng quy mô ứng dụng.
* Tiếp tục nghiên cứu dự án nhóm và hoàn thiện proposal.

### Các công việc trong tuần 5:
| Thứ | Công việc                                                                                                                                                                                   | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu                            |
| --- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------ | --------------- | ----------------------------------------- |
| 2   | - Tìm hiểu hệ sinh thái Database của AWS (Module 06): Ôn tập khái niệm cơ sở dữ liệu, khám phá Amazon RDS, Amazon Aurora, kho dữ liệu Redshift và dịch vụ cache ElastiCache | 20/07/2026   | 20/07/2026      | [Youtube AWS Study Group](https://www.youtube.com/@AWSStudyGroup) |
| 3   | - **Thực hành Lab 10 (Phần 1):** Lưu trữ website tĩnh trên Amazon S3 <br>&emsp; + Tạo bucket S3, upload mã nguồn tĩnh <br>&emsp; + Kích hoạt tính năng web hosting tĩnh <br>&emsp; + Điều chỉnh Block Public Access và mở quyền truy cập cho objects <br>&emsp; + Kiểm tra hiển thị web thực tế <br> - Thảo luận nhóm để hoàn thiện bản đề xuất (proposal) cho dự án cuối khóa | 21/07/2026   | 21/07/2026      | [Lab 10 Hosting Website tĩnh với Amazon S3](https://000057.awsstudygroup.com/vi/) |
| 4   | - **Thực hành Lab 10 (Phần 2):** <br>&emsp; + Sử dụng CloudFront làm CDN: Chặn truy cập trực tiếp vào S3, thiết lập CloudFront distribution và test tốc độ tải trang <br>&emsp; + Quản lý S3: Kích hoạt versioning, di chuyển và sao chép dữ liệu liên khu vực (cross-region) <br>&emsp; + Thu hồi và dọn dẹp tài nguyên | 22/07/2026   | 22/07/2026      | [Lab 10 Hosting Website tĩnh với Amazon S3](https://000057.awsstudygroup.com/vi/) |
| 5   | - **Thực hành Lab 11:** Quản trị Relational Database (RDS) <br>&emsp; + Chuẩn bị môi trường: VPC, Security Groups, và DB Subnet Group <br>&emsp; + Khởi chạy EC2 và RDS instance <br>&emsp; + Kết nối ứng dụng vào database <br>&emsp; + Thực hành sao lưu (backup) và phục hồi (restore) dữ liệu | 23/07/2026   | 23/07/2026      | [Lab 11 Kiến thức cơ bản về cơ sở dữ liệu với Amazon Relational Database Service (RDS)](https://000005.awsstudygroup.com/vi/) |
| 6   | - **Thực hành Lab 12:** Tính năng Auto Scaling trên EC2 <br>&emsp; + Khởi tạo hạ tầng cơ sở: Network, EC2, RDS, và web server <br>&emsp; + Đóng gói Launch Template và cấu hình Load Balancer (Target Group, ALB) <br>&emsp; + Khởi tạo Auto Scaling Group <br>&emsp; + Thực hành test các kịch bản scale: Manual, Scheduled, Dynamic và phân tích Predictive scaling metrics | 24/07/2026   | 24/07/2026      | [Lab 12 Mở rộng quy mô ứng dụng với EC2 Auto Scaling](https://000006.awsstudygroup.com/vi/) |


### Kết quả đạt được tuần 5:

* **Hệ sinh thái Database:** Vận dụng thành thạo Amazon RDS từ bước khởi tạo, kết nối ứng dụng đến sao lưu (backup/restore). Nắm bắt tư duy thiết kế với Aurora, Redshift và ElastiCache.
* **Lưu trữ tĩnh & Phân phối nội dung:** Tự tay thiết lập Static Website bằng S3, kết hợp CloudFront (CDN) giúp tăng tốc độ tải trang toàn cầu. Áp dụng Versioning để quản lý phiên bản file an toàn.
* **Kiến trúc linh hoạt (Auto Scaling):** Xây dựng thành công hệ thống tự động mở rộng (Auto Scaling) kết hợp Load Balancer, thực nghiệm tính hiệu quả qua các kịch bản Manual, Scheduled và Dynamic Scaling.
* **Định hình Dự án:** Hoàn thiện và chốt bản đề xuất (proposal) chính thức cho dự án nhóm (Capstone Project).


