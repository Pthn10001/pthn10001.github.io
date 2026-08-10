---
title: "Worklog Tuần 2"
date: 2026-06-22
weight: 1
chapter: false
pre: " <b> 1.2. </b> "
---

### Mục tiêu tuần 2:

* Thực hành quản lý truy cập người dùng an toàn với AWS IAM.
* Hiểu kiến trúc mạng Amazon VPC và các lớp bảo mật mạng.
* Khởi động dự án nhóm.

### Các công việc trong tuần 2:
| Thứ | Công việc                                                                                                                                                                                   | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu                            |
| --- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------ | --------------- | ----------------------------------------- |
| 2   | - **Thực hành Lab 4 (IAM):** Cấu hình bảo mật và quản lý quyền hạn truy cập. <br>&emsp;  + Khởi tạo Users và Groups trong IAM <br>&emsp; + Thiết lập Policies & Roles <br>&emsp; + Thử nghiệm cơ chế Switch Role an toàn                                                                                         | 29/06/2025   | 29/06/2026      | [Lab 4](https://000002.awsstudygroup.com/vi/) |
| 3   | - **Thực hành Lab 5 (Phần 1 - VPC & Mạng lưới):** <br>&emsp; + Khám phá kiến trúc VPC, khai báo Subnets, cấu hình IGW và NAT Gateway <br>&emsp; + Phân tích cơ chế hoạt động của tường lửa (Security Groups) và ranh giới mạng (NACLs) | 30/06/2026   | 30/06/2026      | [Lab 5 Giới thiệu](https://000003.awsstudygroup.com/vi/1-introduce/) <br> [Lab 5 Tường lửa trong VPC](https://000003.awsstudygroup.com/vi/2-firewallinvpc/) |
| 4   | - **Thực hành Lab 5 (Phần 2 - Triển khai tài nguyên):** <br>&emsp; + Setup môi trường VPC: Cấu hình Route Tables, kích hoạt VPC Flow Logs để giám sát <br>&emsp; + Khởi tạo Amazon EC2: Test SSH/RDP, test NAT Gateway đa vùng (Multi-AZ), phân tích luồng mạng bằng Reachability Analyzer, theo dõi qua CloudWatch | 01/07/2026   | 01/07/2026      | [Lab 5 Các bước chuẩn bị](https://000003.awsstudygroup.com/vi/3-prerequisite/) <br> [Lab 5 Triển khai Amazon EC2 Instances](https://000003.awsstudygroup.com/vi/4-createec2server/) |
| 5   | - **Thực hành Lab 5 (Phần 3 - Kết nối Site-to-Site VPN):** <br>&emsp; + Chuẩn bị hạ tầng: Dựng VPC cho VPN và chạy EC2 Instance giả lập mạng On-premises <br>&emsp; + Khởi tạo kết nối VPN: Thiết lập VGW, CGW, tinh chỉnh VPN Tunnels và thực hành xử lý sự cố (Troubleshooting) | 02/07/2026   | 02/07/2026      | [Lab 5 Tạo môi trường VPN](https://000003.awsstudygroup.com/vi/5-vpnsitetosite/5.1-createvpnenv/) <br> [Lab 5 Cấu hình kết nối VPN](https://000003.awsstudygroup.com/vi/5-vpnsitetosite/5.2-vpnsitetosite/) |
| 6   | - **Dự án nhóm (Capstone):** Brainstorming, thu thập dữ liệu và thảo luận để chốt đề tài | 03/07/2026   | 03/07/2026      | |


### Kết quả đạt được tuần 2:

* **Quản trị danh tính & Truy cập (IAM):** Cấu hình thành công các User, Group, Role trên AWS IAM và thực hành phân quyền theo nguyên tắc đặc quyền tối thiểu (Least Privilege).
* **Thiết kế Mạng & Bảo mật:** Tự tay xây dựng hạ tầng mạng nội bộ với Amazon VPC, phân chia Subnet và bảo vệ luồng dữ liệu thông qua tường lửa Security Groups cùng Network ACLs.
* **Điện toán & Mở rộng kết nối:** Khởi chạy các máy chủ ảo EC2 và thiết lập thành công đường truyền mạng an toàn từ môi trường On-premises lên AWS thông qua giao thức Site-to-Site VPN.
* **Định hướng dự án (Capstone):** Hoàn tất giai đoạn Brainstorming, thu thập dữ liệu và chốt được đề tài khả thi cho dự án nhóm.