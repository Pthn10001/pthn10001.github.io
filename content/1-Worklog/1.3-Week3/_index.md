---
title: "Week 3 Worklog"
date: 2026-06-22
weight: 3
chapter: false
pre: " <b> 1.3. </b> "
---

### Week 3 Objectives:

* Master the configuration and management of AWS Site-to-Site VPN using strongSwan and AWS Transit Gateway.
* Understand and deploy a Hybrid DNS architecture using Amazon Route 53 Resolver for DNS resolution between on-premises and AWS environments.
* Gain hands-on experience with multi-VPC connectivity using VPC Peering and AWS Transit Gateway.
* Strengthen knowledge of AWS Compute services, including EC2, AMI, EBS, Instance Store, User Data, Instance Metadata, and Auto Scaling.

### Week 3 Tasks:
| Day | Task                                                                                                                                                                                                   | Start Date | Completion Date | Reference Material                        |
| --- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ---------- | --------------- | ----------------------------------------- |
| 2   | - **Finalizing Lab 5:** <br>&emsp; + Deploy Site-to-Site VPN: Combine strongSwan and Transit Gateway (Create CGW, TGW, VPN Connections, and update Route Tables) <br>&emsp; + Practice resource cleanup <br>&emsp; + Introduction to Infrastructure as Code via Templates | 06/07/2026   | 06/07/2026      | [Lab 5 Configure VPN using strongSwan with Transit Gateway](https://000003.awsstudygroup.com/vi/5-vpnsitetosite/5.3-vpnsitetosite-optional/) <br> [Lab 5 Clean up Resources](https://000003.awsstudygroup.com/vi/6-cleanup/) <br> [Lab 5 Infrastructure as Code Templates](https://000003.awsstudygroup.com/vi/7-infrastructureascode/)|
| 3   | - **Lab 6 (Hybrid DNS):** Managing hybrid DNS using Amazon Route 53 <br>&emsp; + Provision infrastructure via CloudFormation <br>&emsp; + Set up Microsoft AD and connect to RDGW <br>&emsp; + Configure Route 53 Resolver (Inbound/Outbound Endpoints, Rules) and verify domain resolution | 07/07/2026   | 07/07/2026      | [Lab 6 Hybrid DNS Management with Amazon Route 53](https://000010.awsstudygroup.com/vi/) |
| 4   | - **Lab 7 (VPC Peering):** Inter-network connectivity <br>&emsp; + Use CloudFormation to spin up VPCs and EC2 instances <br>&emsp; + Establish Peering Connections between VPCs <br>&emsp; + Tweak NACLs and enable Cross-Peer DNS resolution | 08/07/2026   | 08/07/2026      | [Lab 7 Network Integration with VPC Peering](https://000019.awsstudygroup.com/vi/) |
| 5   | - **Lab 8 (Transit Gateway):** Centralized routing <br>&emsp; + Launch Transit Gateway and create VPC Attachments <br>&emsp; + Set up TGW Route Tables and update corresponding VPC Route Tables | 09/07/2026   | 09/07/2026      | [Lab 8 Centralized Network Management with AWS Transit Gateway](https://000020.awsstudygroup.com/vi/) |
| 6   | - Review AWS Compute core concepts (Module 03): In-depth look at EC2, AMIs, storage options (EBS, Instance Store), and Auto Scaling mechanisms | 10/07/2026   | 10/07/2026      | [Youtube AWS Study Group](https://www.youtube.com/@AWSStudyGroup) |


### Week 3 Achievements:

* **Enterprise VPN Connectivity:** Successfully built and configured an AWS Site-to-Site VPN using strongSwan directly attached to an AWS Transit Gateway.
* **Hybrid DNS Management:** Implemented Amazon Route 53 Resolver (Inbound/Outbound Endpoints & Rules) to synchronize domain resolution across AWS and on-premises environments.
* **Network Interconnectivity:** Practiced peering and validated traffic flows across multiple VPCs using VPC Peering and Transit Gateway. Mastered routing configuration via Route Tables and Cross-Peer DNS.
* **AWS Compute Ecosystem:** Reviewed and deepened understanding of core EC2 components (AMIs, User/Metadata, EBS/Instance Store storage) and Auto Scaling mechanisms.
