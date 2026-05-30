.

🚀 AWS Three-Tier Architecture Project
👨‍💻 Built & Deployed By

Deepak Misal

📌 Project Overview

I designed and deployed a complete 3-tier architecture on AWS as part of my hands-on DevOps and Cloud learning.

This project was fully implemented in my AWS account by manually configuring networking, compute, and database layers, and validating end-to-end application flow.

The architecture demonstrates how a scalable web application is deployed using modern cloud infrastructure principles.

🏗️ Architecture Diagram

☁️ AWS Services Used
Amazon VPC (Custom Network Design)
Public & Private Subnets across multiple Availability Zones
Internet Gateway (IGW)
NAT Gateway
EC2 Instances (Web + Application Tier)
NGINX Web Server Configuration
PHP Backend Application
Application Load Balancer (ALB)
Auto Scaling Groups
Amazon RDS MySQL Database
Security Groups & Route Tables
🧠 My Implementation Work

I personally implemented the following:

Designed and built VPC architecture from scratch
Created multi-tier subnet structure (Web, App, DB layers)
Configured routing using IGW and NAT Gateway
Deployed EC2 instances for frontend and backend servers
Installed and configured NGINX web server
Set up backend application and connected it with RDS MySQL
Configured Load Balancer and Target Groups
Enabled Auto Scaling for high availability
Verified complete end-to-end connectivity (Browser → App → DB)


⚠️ Challenges Faced & Resolved
CIDR block overlap while designing subnets
NAT Gateway dependency during setup and deletion
Security group communication issues between tiers
NGINX configuration and backend connectivity issues
EC2 to RDS database connection troubleshooting
📸 Screenshots (AWS Proof)

All deployment evidence is available in the:

/Screenshot

Includes:

VPC setup
Subnets configuration
Route tables
Internet Gateway
NAT Gateway
EC2 instances
Load Balancer
Auto Scaling Group
RDS MySQL

## 📂 Project Structure


aws-three-tier-architecture/
│
├── backend/
│   └── PHP application and API files
│
├── database/
│   └── MySQL database scripts
│
├── frontend/
│   └── HTML, CSS and JavaScript files
│
├── infrastructure/
│   ├── frontend_server.md
│   ├── backend_server.md
│   └── nginx_config
│
├── Screenshot/
│   ├── Vpc.png
│   ├── Subnet.png
│   ├── Route Table.png
│   ├── IGW.png
│   ├── NAT.png
│   ├── Ec2 Instance.png
│   ├── Nginx.png
│   ├── Load Balancer.png
│   ├── Auto Scaling Groupe.png
│   └── RDS.png
│
├── aws-three-tier-architecture.png
│
└── README.md


🚀 Key Learnings
AWS networking (VPC, Subnets, Routing)
High availability architecture design
Load balancing and traffic distribution
Auto Scaling and fault tolerance
Real-world cloud deployment troubleshooting
Multi-tier application architecture design
🎯 Final Outcome

Successfully deployed a scalable, highly available 3-tier architecture on AWS, demonstrating real-world DevOps and Cloud engineering skills.

📜 License

This project is for educational and portfolio purposes only.

🙌 Note

This project was implemented using a reference architecture as guidance, but all AWS configurations, deployment steps, and troubleshooting were performed manually.

🔥 Done
