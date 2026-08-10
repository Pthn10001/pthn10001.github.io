---
title: "Worklog Tuần 3"
date: 2026-06-22
weight: 1
chapter: false
pre: " <b> 1.3. </b> "
---

### Mục tiêu tuần 3:

* Nắm vững cách thiết lập và quản lý kết nối Site-to-Site VPN với strongSwan và AWS Transit Gateway.
* Hiểu và triển khai mô hình Hybrid DNS bằng Route 53 Resolver để phân giải tên miền giữa môi trường On-premises và AWS.
* Làm chủ các mô hình kết nối giữa nhiều VPC thông qua VPC Peering và AWS Transit Gateway.
* Hệ thống hóa kiến thức về các dịch vụ Compute trên AWS, bao gồm EC2, AMI, EBS, Instance Store, User Data, Metadata và Auto Scaling.

### Các công việc trong tuần 3:
| Thứ | Công việc                                                                                                                                                                                   | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu                            |
| --- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------ | --------------- | ----------------------------------------- |
| 2   | - **Lab 5 (Kết thúc):** <br>&emsp; + Triển khai Site-to-Site VPN: Dùng strongSwan kết hợp Transit Gateway (Tạo CGW, TGW, VPN Connection và cấu hình Route Tables) <br>&emsp; + Thực hành dọn dẹp tài nguyên (Clean up) <br>&emsp; + Làm quen với Infrastructure as Code Templates | 06/07/2026   | 06/07/2026      | [Lab 5 Cấu hình VPN bằng strongSwan với Transit Gateway](https://000003.awsstudygroup.com/vi/5-vpnsitetosite/5.3-vpnsitetosite-optional/) <br> [Lab 5 Dọn dẹp Tài nguyên](https://000003.awsstudygroup.com/vi/6-cleanup/) <br> [Lab 5 Infrastructure as Code Templates](https://000003.awsstudygroup.com/vi/7-infrastructureascode/)|
| 3   | - **Lab 6 (Hybrid DNS):** Quản trị DNS lai qua Amazon Route 53 <br>&emsp; + Khởi tạo hạ tầng bằng CloudFormation <br>&emsp; + Setup Microsoft AD và kết nối RDGW <br>&emsp; + Cấu hình Route 53 Resolver (Inbound/Outbound Endpoints, Rules) và kiểm tra phân giải tên miền | 07/07/2026   | 07/07/2026      | [Lab 6 Quản lý DNS lai với Amazon Route 53](https://000010.awsstudygroup.com/vi/) |
| 4   | - **Lab 7 (VPC Peering):** Kết nối mạng nội bộ <br>&emsp; + Dùng CloudFormation tạo VPC và EC2 <br>&emsp; + Thiết lập kết nối Peering giữa 2 VPC <br>&emsp; + Tinh chỉnh NACL và bật tính năng phân giải DNS chéo (Cross-Peer DNS) | 08/07/2026   | 08/07/2026      | [Lab 7 Tích hợp mạng với VPC Peering](https://000019.awsstudygroup.com/vi/) |
| 5   | - **Lab 8 (Transit Gateway):** Định tuyến mạng tập trung <br>&emsp; + Khởi tạo Transit Gateway và kết nối các VPC (Attachments) <br>&emsp; + Cấu hình TGW Route Tables và cập nhật VPC Route Tables | 09/07/2026   | 09/07/2026      | [Lab 8 Quản lý mạng tập trung với AWS Transit Gateway](https://000020.awsstudygroup.com/vi/) |
| 6   | - Ôn tập lý thuyết về Điện toán đám mây (Module 03): Phân tích sâu về EC2, AMI, các loại lưu trữ (EBS, Instance Store) và cơ chế Auto Scaling | 10/07/2026   | 10/07/2026      | [Youtube AWS Study Group](https://www.youtube.com/@AWSStudyGroup) |


### Kết quả đạt được tuần 3:

* **Kết nối VPN Doanh nghiệp:** Dựng và cấu hình thành công AWS Site-to-Site VPN bằng strongSwan kết nối thẳng vào AWS Transit Gateway.
* **Quản trị DNS lai (Hybrid DNS):** Áp dụng Amazon Route 53 Resolver (Inbound/Outbound Endpoints & Rules) để đồng bộ phân giải tên miền giữa môi trường AWS và On-premises.
* **Định tuyến liên kết mạng:** Thực hành ghép nối và kiểm thử luồng traffic giữa nhiều VPC với nhau thông qua VPC Peering và Transit Gateway. Làm chủ các bảng định tuyến (Route Tables) và tính năng Cross-Peer DNS.
* **Nền tảng Compute AWS:** Ôn tập và đào sâu các thành phần lõi của EC2 (AMI, User/Metadata, cấu hình ổ cứng EBS/Instance Store) và cơ chế tự động mở rộng Auto Scaling.


