---
title: "Worklog Tuần 7"
date: 2026-06-22
weight: 1
chapter: false
pre: " <b> 1.7. </b> "
---

### Mục tiêu tuần 7:

* Nắm vững cách triển khai và quản lý Amazon ElastiCache bằng AWS SDK và AWS CLI.
* Hiểu và thực hành các kiến thức mạng nâng cao trên AWS, bao gồm Transit Gateway, Site-to-Site VPN, Route 53, VPC Endpoints và VPC Peering.
* Xây dựng và quản lý hạ tầng dưới dạng mã với AWS CloudFormation.
* Tìm hiểu các tính năng nâng cao của CloudFormation như Custom Resources, StackSets và Drift Detection.
* Tiếp tục hoàn thiện dự án nhóm và xây dựng nội dung workshop.

### Các công việc trong tuần 7:
| Thứ | Công việc                                                                                                                                                                                   | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu                            |
| --- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------ | --------------- | ----------------------------------------- |
| 2   | - **Lab 16 (Tiếp theo):** Quản trị ElastiCache <br>&emsp; + Phân quyền, kết nối node và thao tác xóa cluster qua Console/CLI <br>&emsp; + Dùng AWS SDK để đọc/ghi bộ nhớ đệm: Tạo cluster, Set/Get dữ liệu (string, hash), cấu hình Publish/Subscribe và thao tác với Stream <br>&emsp; + Dọn dẹp tài nguyên | 03/08/2026   | 03/08/2026      |[Lab 16 Bộ nhớ đệm trong bộ nhớ với Amazon ElastiCache](https://000061.awsstudygroup.com/vi/)|
| 3   | - **Lab 17 (Phần 1):** AWS Networking Workshop <br>&emsp; + Phân tích chuyên sâu các thành phần mạng (VPC Components) <br>&emsp; + Setup hạ tầng: Triển khai VPC và cấu hình Cisco CSR <br>&emsp; + Kết nối Transit Gateway & Site-to-Site VPN: Định tuyến TGW, cài đặt IPsec VPN, và thiết lập đường truyền ECMP | 04/08/2026   | 04/08/2026      | [Lab 17 Workshop về mạng trên AWS](https://000092.awsstudygroup.com/vi/) |
| 4   | - **Lab 17 (Phần 2):** <br>&emsp; + Phân giải tên miền nội bộ bằng Route53 DNS Endpoints <br>&emsp; + Triển khai bảo mật truy cập qua VPC Endpoints (Interface/Gateway) cho các dịch vụ AWS <br>&emsp; + Cấu hình VPC Peering và bảng định tuyến liên mạng <br>&emsp; + Quản trị và giám sát với Transit Gateway Network Manager <br>&emsp; + Thu hồi tài nguyên đã tạo| 05/08/2026   | 05/08/2026      | [Lab 17 Workshop về mạng trên AWS](https://000092.awsstudygroup.com/vi/) |
| 5   | - **Lab 18 (Cơ bản):** Infrastructure as Code bằng CloudFormation <br>&emsp; + Cấu hình quyền (IAM User/Role) để chuẩn bị môi trường <br>&emsp; + Viết và triển khai mẫu hạ tầng (CloudFormation Template) cơ bản đầu tiên | 06/08/2026   | 06/08/2026      | [Lab 18 Hạ tầng dưới dạng mã với AWS CloudFormation](https://000037.awsstudygroup.com/vi/) |
| 6   | - **Lab 18 (Nâng cao):** <br>&emsp; + Vận dụng Custom Resources (Tích hợp Lambda để cấu hình EC2) <br>&emsp; + Triển khai hạ tầng trên nhiều account/region bằng Mappings và StackSets <br>&emsp; + Giám sát thay đổi hạ tầng bằng Drift Detection <br>&emsp; + Dọn dẹp tài nguyên <br> - Hoàn tất nội dung và ghép nối các thành phần của dự án cuối khóa | 07/08/2026   | 07/08/2026      | [Lab 18 Hạ tầng dưới dạng mã với AWS CloudFormation](https://000037.awsstudygroup.com/vi/) |


### Kết quả đạt được tuần 7:

* **Thao tác Cache chuyên sâu:** Sử dụng thành thạo AWS SDK để kết nối và lập trình tương tác (đọc/ghi String, Hash, Stream) trực tiếp với Amazon ElastiCache.
* **Hạ tầng Mạng nâng cao:** Triển khai thành công cụm mạng phức tạp: thiết lập Site-to-Site VPN nối vào Transit Gateway, cấu hình DNS nội bộ (Route 53) và bảo mật truy cập bằng VPC Endpoints.
* **Infrastructure as Code (IaC):** Chuyển đổi tư duy từ cấu hình thủ công sang tự động hóa toàn phần bằng AWS CloudFormation. Khám phá các tính năng mạnh mẽ như Custom Resources, StackSets và Drift Detection.
* **Cột mốc Workshop:** Cơ bản hoàn tất việc tổng hợp nội dung và kịch bản cho buổi Workshop cuối khóa của nhóm.