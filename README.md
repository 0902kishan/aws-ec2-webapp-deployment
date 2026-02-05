# AWS EC2 Web Application Deployment

This repository documents my hands-on experience deploying a PHP–MySQL based web application on AWS EC2 using the AWS Free Tier.

The focus of this repository is **cloud infrastructure, deployment, security configuration, and cost management**, not application development.

---

## 🚀 Services Used
- AWS EC2 (Ubuntu Linux)
- AWS Security Groups
- SSH
- Apache Web Server
- PHP
- MySQL
- AWS Free Tier

---

## 🧩 Deployment Summary
- Created and launched an EC2 instance in the us-east-1 region
- Used Free Tier eligible instance type (t3.micro)
- Connected to the instance using SSH key authentication
- Installed Apache, PHP, and MySQL
- Deployed the Alumni Management System
- Configured security groups for controlled access
- Verified public accessibility using EC2 public IP
- Stopped and terminated the instance to avoid billing

---

## 🔐 Security Configuration
- SSH (port 22) allowed for administration
- HTTP (port 80) allowed for web access
- No unnecessary ports opened
- Database access restricted to the local instance only

---

## 💰 Cost Management
Cost-saving practices are documented here:
➡️ `deployment-guide/cost-management.md`

---

## 📸 Screenshots
- EC2 Instance dashboard
- Security Group rules
- Live website hosted on EC2

---

## 🔗 Project Reference
The deployed application source code:

➡️ https://github.com/0902kishan/0902kishan-alumni-management-system

This separation of **application code** and **cloud infrastructure** reflects real-world cloud engineering practices.
