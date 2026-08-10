---
title: "Week 7 Worklog"
date: 2026-06-22
weight: 7
chapter: false
pre: " <b> 1.7. </b> "
---

### Week 7 Objectives:

* Master the deployment and management of Amazon ElastiCache using AWS SDK and AWS CLI.
* Understand and practice advanced AWS networking concepts, including Transit Gateway, Site-to-Site VPN, Route 53, VPC Endpoints, and VPC Peering.
* Build and manage Infrastructure as Code (IaC) using AWS CloudFormation.
* Explore advanced CloudFormation features such as Custom Resources, StackSets, and Drift Detection.
* Continue improving the group project and developing the workshop content.

### Week 7 Tasks:

| Day | Tasks | Start Date | Completion Date | Reference Material |
| --- | --- | --- | --- | --- |
| 2 | - **Lab 16 (Part 2):** ElastiCache Administration <br>&emsp; + Manage node connections, permissions, and cluster deletion via Console/CLI <br>&emsp; + Programmatic access via AWS SDK: Instantiate clusters, perform Set/Get operations on strings and hashes, configure Pub/Sub messaging, and process Streams <br>&emsp; + Resource cleanup | 03/08/2026 | 03/08/2026 | [Lab 16 In-Memory Caching with Amazon ElastiCache](https://000061.awsstudygroup.com/vi/) |
| 3 | - **Lab 17 (Part 1):** AWS Networking Workshop <br>&emsp; + Deep dive into core VPC components <br>&emsp; + Infrastructure scaffolding: Provision VPCs and accept Cisco CSR agreements <br>&emsp; + Establish Transit Gateway & Site-to-Site VPNs: Access Cisco CSR via Cloud9, set up IPSec tunnels, and configure ECMP routing paths | 04/08/2026 | 04/08/2026 | [Lab 17 AWS Networking Workshop](https://000092.awsstudygroup.com/vi/) |
| 4 | - **Lab 17 (Part 2):** <br>&emsp; + Private DNS resolution using Route 53 Endpoints and Internal Hosted Zones <br>&emsp; + Secure AWS service access via VPC Endpoints and Endpoint Services <br>&emsp; + Configure inter-VPC connectivity with VPC Peering and cross-account routing <br>&emsp; + Centralized network visualization via Transit Gateway Network Manager <br>&emsp; + Environment teardown | 05/08/2026 | 05/08/2026 | [Lab 17 AWS Networking Workshop](https://000092.awsstudygroup.com/vi/) |
| 5 | - **Lab 18 (Basics):** Infrastructure as Code via CloudFormation <br>&emsp; + Prepare the IAM environment (Users & Roles) <br>&emsp; + Provision a dedicated workspace and deploy the first basic CloudFormation Template | 06/08/2026 | 06/08/2026 | [Lab 18 Infrastructure as Code with AWS CloudFormation](https://000037.awsstudygroup.com/vi/) |
| 6 | - **Lab 18 (Advanced):** <br>&emsp; + Implement Custom Resources (Triggering Lambda to orchestrate EC2) <br>&emsp; + Multi-region deployments with Mappings and StackSets <br>&emsp; + Monitor infrastructure deviations using Drift Detection <br>&emsp; + Final cleanup <br> - Wrap up documentation and finalize the team capstone project deliverables | 07/08/2026 | 07/08/2026 | [Lab 18 Infrastructure as Code with AWS CloudFormation](https://000037.awsstudygroup.com/vi/) |

### Week 7 Achievements:

* **Advanced Caching Operations:** Leveraged the AWS SDK to programmatically connect and interact (read/write Strings, Hashes, Streams) directly with Amazon ElastiCache.
* **Advanced Cloud Networking:** Successfully deployed complex network topologies: routing Site-to-Site VPNs through Transit Gateways, configuring internal DNS via Route 53, and securing service access with VPC Endpoints.
* **Infrastructure as Code (IaC):** Transitioned from manual provisioning to fully automated deployments using AWS CloudFormation. Explored powerful IaC features like Custom Resources, StackSets, and Drift Detection.
* **Workshop Milestone:** Substantially finalized the content aggregation and scripting for the team's capstone Workshop presentation.