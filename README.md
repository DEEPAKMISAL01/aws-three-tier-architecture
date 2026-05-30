# AWS Three-Tier Architecture Project (Custom Implementation)

## 👨‍💻 Author
Deepak Misal

## 📌 Project Overview

This project demonstrates a fully deployed **3-tier architecture on AWS** using real-world DevOps practices.

It includes:
- Frontend Tier (NGINX on EC2)
- Backend Tier (PHP Application Server)
- Database Tier (Amazon RDS MySQL)

The infrastructure was manually designed, configured, and tested on AWS using VPC, subnets, load balancers, and auto scaling.

---

## 🏗️ Architecture Diagram

![Architecture](aws-three-tier-architecture.png)

---

## ☁️ AWS Services Used

- Amazon VPC (Custom Network)
- Public & Private Subnets
- Internet Gateway (IGW)
- NAT Gateway
- EC2 Instances (Web + App Tier)
- Application Load Balancer (ALB)
- Auto Scaling Groups
- Amazon RDS (MySQL)
- Security Groups
- Route Tables

---

## 🖼️ Proof of Implementation (Screenshots)

All real AWS deployment screenshots are available in the `Screenshot/` folder:

- VPC Setup
- Subnets Configuration
- Route Tables
- Internet Gateway
- NAT Gateway
- EC2 Instances
- NGINX Server Setup
- Load Balancer
- Auto Scaling Group
- RDS Database

---

## 🧠 My Contributions

This project was not just deployed — it was fully configured and troubleshot manually:

- Designed custom VPC architecture
- Created multi-AZ subnet architecture
- Configured routing (IGW + NAT)
- Set up EC2 instances for web and application tiers
- Installed and configured NGINX and PHP backend
- Connected application with RDS MySQL database
- Configured Load Balancers and Target Groups
- Fixed issues like:
  - CIDR overlap errors
  - NAT Gateway dependency issues
  - Security group misconfigurations

---

## ⚠️ Challenges Faced

- CIDR block planning for multi-subnet architecture
- NAT Gateway dependency during cleanup
- Security group communication between tiers
- Debugging NGINX and backend connectivity

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

- VPC design and subnet planning
- Load balancing and high availability
- Auto Scaling concepts
- Multi-tier architecture design
- AWS networking fundamentals
- Real-world deployment troubleshooting

---

## 📸 Screenshots

Refer to `/Screenshot` folder for full AWS deployment evidence.

---

## 📜 License

This project is for learning and DevOps portfolio purposes.

---

## 🙌 Conclusion

This project demonstrates hands-on AWS DevOps skills by deploying a scalable and highly available three-tier architecture in a real cloud environment.
