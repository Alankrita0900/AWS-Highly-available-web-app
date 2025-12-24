# 🚀 Highly Available Web Application on AWS

A hands-on AWS cloud project demonstrating how to design and deploy a **secure, scalable, and highly available web application** using core AWS services such as **VPC, EC2, S3, SNS, and CloudWatch**.

---

## 📌 Project Overview

This project focuses on building a production-style AWS architecture that follows **cloud security best practices**, includes **monitoring & alerting**, and supports **high availability** for web applications.

**Key goals:**
- Secure networking using a custom VPC
- Public access to the web application via EC2
- Static content and backups using S3
- Real-time alerts using SNS and CloudWatch

---

## 🏗️ Architecture Overview

### 🔹 Architecture Components
- **Amazon VPC** – Custom VPC for isolated networking
- **Public Subnet** – Hosts the EC2 instance
- **Internet Gateway** – Enables internet access
- **Route Table** – Routes traffic to the IGW
- **EC2 (Amazon Linux 2)** – Hosts the web application
- **Security Groups** – Controls inbound & outbound traffic
- **Amazon S3** – Stores static files and backups
- **IAM Role** – Secure access to S3 from EC2
- **Amazon SNS** – Sends alert notifications
- **Amazon CloudWatch** – Monitors system metrics

