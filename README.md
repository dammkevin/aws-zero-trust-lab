# AWS Zero Trust Security Lab

**Cloud Security | IAM | Automation**

This project demonstrates the implementation of Zero Trust principles within AWS using IAM, EC2, S3, GuardDuty, and CloudTrail.  

It includes Python and Go automation scripts for auditing cloud resources, identifying misconfigurations, and enforcing least privilege.

## 🏗 Architecture
![Zero Trust Diagram] (architecture/zero-trust-diagram.png)

## 🔐 Key Features
- Enforced MFA and least-privilege IAM roles across users and services
- Implemented network segmentation via VPC subnets and Security Groups
- Enabled continuous monitoring through GuardDuty and CloudTrail
- Automated cloud audits using Python (boto3) and Go (aws-sdk-go)

## 🧠 Lessons Learned
- Importance of identity-based policies over static network rules
- How continuous monitoring supports Zero Trust enforcement
- Value of automation for rapid misconfiguration detection

## 🧰 Technologies Used
AWS EC2 | S3 | VPC | IAM | GuardDuty | CloudTrail | Python | Go | boto3 | aws-sdk-go
