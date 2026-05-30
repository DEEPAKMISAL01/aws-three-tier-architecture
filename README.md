# AWS Three-Tier Architecture Deployment Project

## 👨‍💻 Built & Deployed By
Deepak Misal

---

## 📌 Project Summary

I designed and deployed a complete **3-tier architecture on AWS** as part of my DevOps learning and hands-on cloud practice.

The entire infrastructure was manually built using AWS console and tested end-to-end with real EC2, networking, and database connectivity.

---

## 🏗️ Architecture Design

![Architecture](aws-three-tier-architecture.png)

---

## ☁️ AWS Services I Used

- VPC (custom network design)
- Public & Private Subnets across multiple AZs
- Internet Gateway (IGW)
- NAT Gateway for private subnet access
- EC2 instances for Web and Application tiers
- NGINX configured on frontend servers
- PHP backend application setup
- Application Load Balancer (ALB)
- Auto Scaling Groups for high availability
- Amazon RDS MySQL database
- Security Groups and Route Tables

---

## 🧠 What I Actually Did (My Work)

- Designed a full VPC architecture from scratch
- Planned subnetting for web, app, and database layers
- Configured routing between public and private networks
- Deployed EC2 instances and configured NGINX manually
- Set up backend PHP application and connected it with RDS MySQL
- Configured Load Balancers and Target Groups
- Enabled Auto Scaling for high availability
- Verified full end-to-end traffic flow from browser → database

---

## ⚠️ Issues I Faced & Solved

- Fixed CIDR overlap errors while designing subnets
- Resolved NAT Gateway dependency issues during setup and cleanup
- Debugged security group communication between tiers
- Fixed NGINX and backend connectivity issues
- Handled EC2-to-RDS connection configuration issues

---

## 📸 AWS Implementation Evidence

All real AWS setup screenshots are available in:

/Screenshot

Includes:
- VPC configuration
- Subnets
- Route tables
- Internet Gateway
- NAT Gateway
- EC2 instances
- Load Balancer
- Auto Scaling Group
- RDS setup

---

## 📂 Project Structure
backend/
database/
frontend/
infrastructure/
Screenshot/
aws-three-tier-architecture.png
README.md


---

## 🚀 Key Learnings

- Real-world AWS networking (VPC, routing, subnets)
- Load balancing and high availability concepts
- Auto Scaling and fault tolerance
- Multi-tier application architecture design
- Troubleshooting cloud infrastructure issues

---

## 🎯 Project Outcome

Successfully deployed a fully working **scalable three-tier architecture on AWS**, with proper separation of frontend, backend, and database layers.

This project helped me gain practical experience in cloud infrastructure and DevOps deployment workflows.
