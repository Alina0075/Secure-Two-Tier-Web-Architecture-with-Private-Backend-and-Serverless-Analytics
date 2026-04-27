# 🚀 Secure Two-Tier Web Architecture with Private Backend and Serverless Analytics

## 📌 Overview

This project demonstrates a **production-ready AWS cloud architecture** for a secure and scalable web application. It follows a **two-tier design**, separating the frontend and backend while ensuring high availability, automation, and security.

The system integrates **serverless analytics** to automatically generate and send reports, simulating a real-world cloud deployment.

---

## 🎯 Objectives

* Build a **secure two-tier architecture**
* Implement **network isolation using private subnets**
* Deploy a **managed database (RDS)**
* Enable **auto-scaling and load balancing**
* Automate infrastructure using **Infrastructure as Code (IaC)**
* Integrate **serverless analytics using Lambda**

---

## 🏗️ Architecture

```
User → S3 / Load Balancer → EC2 (App Server) → RDS (Database)
                                      ↓
                              Lambda → SNS (Email Reports)
```

---

## ⚙️ Technologies Used

* AWS S3 – Static website hosting
* AWS EC2 – Application server (LAMP stack)
* AWS RDS – Managed database
* AWS VPC – Network isolation
* AWS Auto Scaling – Dynamic scaling
* Elastic Load Balancer – Traffic distribution
* AWS CloudFormation – Infrastructure as Code
* AWS CodePipeline – CI/CD automation
* AWS Lambda – Serverless computing
* Amazon SNS – Notifications

---

## 📂 Project Phases

### 🔹 Phase 1: Frontend Hosting

* Hosted static website using S3
* Enabled lifecycle policies and replication

### 🔹 Phase 2: Application Server

* Deployed EC2 instance
* Installed Apache, PHP, and MySQL
* Configured LAMP stack

### 🔹 Phase 3: Network Isolation

* Created custom VPC
* Configured public/private subnets
* Used Bastion host for secure access

### 🔹 Phase 4: Database Integration

* Deployed RDS in private subnet
* Connected EC2 to RDS securely

### 🔹 Phase 5: Auto Scaling & Load Balancing

* Configured Auto Scaling Group
* Implemented Application Load Balancer

### 🔹 Phase 6: Deployment Automation

* Created CloudFormation templates
* Integrated GitHub with CodePipeline

### 🔹 Phase 7: Serverless Analytics

* Built Lambda function for sales reports
* Triggered using EventBridge
* Sent reports via SNS email

---

## 🔐 Security Features

* Private EC2 and RDS instances
* Bastion host for controlled access
* Security groups and NACLs
* IAM roles and policies

---

## 🔄 Workflow

1. User accesses website via S3 or Load Balancer
2. Requests handled by EC2 application server
3. Data stored and retrieved from RDS
4. Lambda processes data daily
5. SNS sends automated email reports

---

## ✅ Key Features

✔ Secure architecture with private backend
✔ High availability with auto-scaling
✔ Fully automated deployment
✔ Serverless analytics integration
✔ Disaster recovery using S3 replication

---

## 📸 Screenshots

(Add your lab screenshots here)

---

## 📚 Conclusion

This project successfully simulates a **real-world cloud deployment** with a focus on security, scalability, and automation. It demonstrates how multiple AWS services can be integrated to build a robust and efficient infrastructure.

---

## 👩‍💻 Author

**Alina Akhtar**
BSCS – UCP Lahore

---
