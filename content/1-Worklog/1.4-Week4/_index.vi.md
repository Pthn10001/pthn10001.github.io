---
title: "Worklog Tuần 4"
date: 2026-06-22
weight: 1
chapter: false
pre: " <b> 1.4. </b> "
---

### Mục tiêu tuần 4:

* Nắm vững cách khởi tạo, cấu hình và quản lý Amazon EC2 trên Windows và Linux.
* Thành thạo các thao tác quản trị EC2 như Snapshot, AMI, khôi phục truy cập và triển khai ứng dụng Node.js.
* Hiểu và áp dụng IAM để quản lý quyền truy cập và kiểm soát tài nguyên AWS.
* Hệ thống hóa kiến thức về các dịch vụ lưu trữ trên AWS (Amazon S3, Glacier, Storage Gateway, Backup).
* Nắm được các dịch vụ bảo mật cốt lõi trên AWS và tiếp tục nghiên cứu dự án nhóm.

### Các công việc trong tuần 4:
| Thứ | Công việc                                                                                                                                                                                   | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu                            |
| --- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------ | --------------- | ----------------------------------------- |
| 2   | - **Thực hành Lab 9 (Phần 1 - EC2 Cơ bản):** <br>&emsp; + Chuẩn bị hạ tầng mạng riêng (VPC) và Security Group cho Windows/Linux <br>&emsp; + Khởi tạo và truy cập thử vào các máy chủ ảo (Windows Server và Linux Instance) | 13/07/2026   | 13/07/2026      | [Lab 9 Giới thiệu](https://000004.awsstudygroup.com/vi/1-introduce/) <br> [Lab 9 Các bước chuẩn bị](https://000004.awsstudygroup.com/vi/2-prerequiste/) <br> [Lab 9 Khởi tạo Windows instance](https://000004.awsstudygroup.com/vi/3-launchwindowsinstance/) <br> [Lab 9 Khởi tạo Linux instance](https://000004.awsstudygroup.com/vi/4-launchlinuxinstance/)|
| 3   | - **Thực hành Lab 9 (Phần 2 - Nâng cao):** <br>&emsp; + Thao tác quản trị EC2: Đổi cấu hình, chụp Snapshots, đóng gói Custom AMI, khôi phục quyền truy cập (qua SSM hoặc User Data) <br>&emsp; + Cài đặt giao diện Desktop cho Ubuntu <br>&emsp; + Triển khai web app Node.js: Cài cắm môi trường LAMP/XAMPP trên cả Linux và Windows EC2 | 14/07/2026   | 14/07/2026      | [Lab 9 Amazon EC2 cơ bản](https://000004.awsstudygroup.com/vi/5-amazonec2basic/) <br> [Lab 9 Triển khai ứng dụng Node.js trên Amazon Linux](https://000004.awsstudygroup.com/vi/6-awsfcjmanagement-linux/) <br> [Lab 9 Ứng dụng Node.js trên Amazon EC2 Windows](https://000004.awsstudygroup.com/vi/7-awsfcjmanagement-windows/) |
| 4   | - **Thực hành Lab 9 (Phần 3 - Tối ưu & Bảo mật):** <br>&emsp; + Áp dụng IAM Policies để giới hạn region, dòng máy (Instance Family), chuẩn ổ cứng (EBS type), và chặn xoá tài nguyên theo IP/thời gian <br>&emsp; + Dọn dẹp tài nguyên (Clean up) <br> - Thảo luận, đẩy mạnh tiến độ dự án nhóm (Capstone) | 15/07/2026   | 15/07/2026      | [Lab 9 Giới hạn sử dụng tài nguyên bằng dịch vụ IAM](https://000004.awsstudygroup.com/vi/8-costusagegovernance/) <br> [Lab 9 Dọn dẹp tài nguyên](https://000004.awsstudygroup.com/vi/9-cleanup/) |
| 5   | - Khám phá các dịch vụ Lưu trữ đám mây (Module 04): Đi sâu vào Amazon S3 (Access Point, Storage Class, Static Web, CORS), lưu trữ lạnh Glacier và các giải pháp Backup, Storage Gateway | 16/07/2026   | 16/07/2026      | [Youtube AWS Study Group](https://www.youtube.com/@AWSStudyGroup) |
| 6   | - Tìm hiểu mô hình bảo mật trên AWS (Module 05): Shared Responsibility Model, quản trị định danh (IAM, Cognito, IAM Identity Center), mã hoá (KMS) và giám sát (Security Hub) | 17/07/2026   | 17/07/2026      | [Youtube AWS Study Group](https://www.youtube.com/@AWSStudyGroup) |


### Kết quả đạt được tuần 4:

* **Quản trị EC2 Thực chiến:** Thành thạo các thao tác khởi tạo, đóng gói AMI, chụp Snapshots và xử lý sự cố mất key truy cập trên cả môi trường Windows lẫn Linux.
* **Triển khai Ứng dụng:** Tự tay cài đặt môi trường (LAMP/XAMPP) và đưa thành công một web app Node.js lên chạy thực tế trên máy chủ EC2.
* **Tối ưu & Quản lý Tài nguyên (IAM):** Biết cách viết IAM Policies để thắt chặt bảo mật: giới hạn quyền tạo tài nguyên theo vùng (region), dòng máy (instance type) và chặn xóa tài nguyên bừa bãi.
* **Kiến thức Lưu trữ & Bảo mật:** Nắm bắt cơ chế hoạt động của hệ sinh thái lưu trữ (S3, Glacier, Storage Gateway) và bộ công cụ bảo mật chuyên sâu của AWS (KMS, Cognito, Security Hub).
* **Tiến độ Dự án:** Tiếp tục thúc đẩy quá trình lên khung kiến trúc và chuẩn bị dữ liệu cho đồ án cuối khóa.


