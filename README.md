🔐 Lab 18: Enterprise IAM Security & Identity Governance (REAL JOB MODE)

📌 Overview

This project demonstrates the implementation of enterprise-grade Identity and Access Management (IAM) and secure audit logging controls in AWS.

The lab focuses on enforcing least privilege access, multi-factor authentication (MFA), secure role-based access control (RBAC), and tamper-proof logging using CloudTrail, S3 Object Lock, and AWS KMS.

🎯 Objectives
Implement secure IAM policies and roles
Enforce Multi-Factor Authentication (MFA)
Configure CloudTrail for audit logging
Secure logs using S3 Object Lock (WORM)
Encrypt logs with AWS KMS
Monitor activity using CloudWatch Logs
Validate access using EC2 + IAM roles + SSM Session Manager

🏗️ Architecture

This lab simulates a real-world enterprise security setup:

IAM Users & Groups (Admin / Non-MFA User)
IAM Roles for EC2 access
AWS CloudTrail for logging
S3 Bucket with Object Lock enabled
AWS KMS for encryption
CloudWatch Logs for monitoring
EC2 instance for validation testing
AWS Systems Manager (SSM) for secure access
⚙️ Technologies Used
AWS IAM
AWS CloudTrail
Amazon S3 (Object Lock Enabled)
AWS KMS
Amazon CloudWatch
Amazon EC2
AWS Systems Manager (SSM)
🔐 Key Security Implementations
✅ Identity & Access Control
Created IAM users and groups
Assigned least privilege policies
Configured admin group with elevated permissions
Enforced MFA for secure authentication
Identified risks of users without MFA
✅ Role-Based Access Control (RBAC)
Created IAM role for EC2 instance
Attached appropriate trust policies
Enabled secure access without hardcoded credentials
✅ Audit Logging & Monitoring
Enabled AWS CloudTrail for account-wide logging
Integrated CloudTrail with CloudWatch Logs
Verified log streams and activity tracking
✅ Data Protection & Compliance
Created S3 bucket for CloudTrail logs
Enabled Object Lock (WORM) for immutability
Enabled versioning for log integrity
Configured AWS KMS encryption
✅ Secure Access Validation
Launched EC2 instance with IAM role
Verified secure access using SSM Session Manager
Tested SSH and role-based authentication
📸 Screenshots

All implementation steps and validations are documented in this repository:

IAM Dashboard configuration
MFA setup
CloudTrail creation
KMS key setup
S3 bucket with Object Lock
CloudWatch logs
EC2 instance validation
SSM session logs
🧠 Key Learnings
Implementing enterprise IAM governance
Enforcing Zero Trust security principles
Securing logs with WORM compliance (Object Lock)
Using KMS for encryption and key management
Monitoring cloud environments using CloudTrail + CloudWatch
Eliminating credential exposure using IAM roles + SSM
🚀 Real-World Relevance

This lab aligns with:

ISO 27001 (Access Control & Logging)
NCSC CAF (Identity & Monitoring Controls)
SOC 2 (Security & Audit Logging)
AWS Well-Architected Framework – Security Pillar
📂 Project Structure
Lab 18 Enterprise IAM Security & Identity Governance/
│
├── Screenshots/
├── README.md
└── Notes/
📢 Author

Ime Ben
AWS Cloud Security Engineer | DevSecOps | AI Security

🌍 Location: Glasgow, United Kingdom
💼 GitHub: https://github.com/ime-cloud-sec-analyst
🔗 LinkedIn: (Add your LinkedIn link here)
🏷️ Hashtags
#AWS #CloudSecurity #IAM #CyberSecurity #DevSecOps #CloudTrail  
#AWSKMS #S3ObjectLock #ZeroTrust #SecurityEngineering  
#CloudWatch #AWSLabs #TechPortfolio #ISO27001 #SOC2  
#NCSC #SecurityMonitoring #AWSProjects #CloudEngineer  

