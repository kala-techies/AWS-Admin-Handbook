
# 🚀 AWS Admin Zero to Hero

**Empowering everyone to master AWS Administration — no prior IT experience required!**

Welcome to **AWS Admin Zero to Hero**, your step-by-step guide to mastering AWS through hands-on labs, clear explanations, and real-world projects. This repository breaks down complex cloud concepts into **beginner-friendly modules**, focusing on the **"why"** and **"how"** behind AWS services. By the end of Phase 3, you’ll design enterprise-grade architectures!

---

## 🌟 Why This Series?
- **Zero Fluff, All Practical**: Learn by doing with guided labs and projects.
- **No Prior Experience Needed**: Start from absolute basics (what’s a server?) to cloud-native architectures.
- **Community-Driven**: Contributions welcome! Fix typos, add labs, or improve explanations.
- **Free Forever**: Open-source and MIT-licensed. 

---

## 🗺️ Learning Path
**Phase 1: Foundations** → **Phase 2: Advanced Networking & Security** → **Phase 3: DevOps & Enterprise Architectures**

---

## 🗂️ Phase 1: Foundations of AWS Administration

### **Module 1: Cloud Foundations**  
🛠️ **Skills**: Understand cloud basics, deployment models, and client-server interactions.  
1. **Introduction to Cloud Computing**  
   - What is the cloud? Key benefits: Scalability, cost-efficiency, flexibility.  
2. **Public vs. Private vs. Hybrid Cloud**  
   - Use cases, pros/cons, and real-world examples (Netflix, Airbnb).  
3. **Client-Server Model Simplified**  
   - How your browser connects to AWS servers (HTTP, DNS basics).  
4. **Physical vs. Logical Infrastructure**  
   - Behind the scenes: AWS data centers vs. virtual resources (EC2, S3).  

### **Module 2: Networking Essentials**  
🛠️ **Skills**: Design secure networks with subnets, gateways, and VPCs.  
5. **IP Addressing & Subnetting**  
   - Public vs. Private IPs, CIDR notation, and subnet design.  
6. **Network Isolation Strategies**  
   - Public subnets (web servers) vs. Private subnets (databases).  
7. **Key AWS Networking Services**  
   - **NAT Gateway**: Outbound internet for private instances.  
   - **VPC Peering**: Connect VPCs securely (local and global).  
   - **Security Groups vs. NACLs**: Stateful vs. stateless traffic control.  

### **Module 3: Building Your First VPC**  
🛠️ **Skills**: Deploy a production-ready network infrastructure.  
8. **Hands-On Lab: Deploy a VPC**  
   - Step-by-step: Internet Gateway, Route Tables, NAT Gateway.  
9. **Launch Templates & EC2 Instances**  
   - Why templates? Launch web servers in public/private subnets.  

### **Module 4: Security & IAM**  
🛠️ **Skills**: Secure AWS resources with least-privilege access.  
10. **IAM Deep Dive**  
    - Users, Groups, Roles, Policies (JSON examples).  
11. **AuthN vs. AuthZ**  
    - MFA, password policies, and permission boundaries.  
12. **AWS Organizations**  
    - Multi-account strategies for enterprises.  

### **Module 5: Automation & IaC**  
🛠️ **Skills**: Automate deployments with AWS CLI and CloudFormation.  
13. **AWS CLI Basics**  
    - Install, configure, and manage EC2 instances via CLI.  
14. **Infrastructure as Code (IaC)**  
    - Deploy a VPC using CloudFormation templates.  

### **Phase 1 Final Project**  
🎯 **Build a Secure 2-Tier Architecture**  
- Web server (public subnet) + Database (private subnet) + IAM roles.  
- **Bonus**: Automate deployment with CloudFormation!  

---

## 🗂️ Phase 2: Advanced Networking, Security & Scalability  
*(For semi-intermediate learners)*  

### **Module 1: Advanced VPC Architectures**  
🛠️ **Skills**: Connect multi-region VPCs, optimize traffic flow.  
1. **VPC Peering Deep Dive**  
   - Cross-region/account peering, route table configurations.  
2. **VPC Endpoints**  
   - Private access to S3/DynamoDB (Gateway vs. Interface Endpoints).  
3. **Transit Gateway**  
   - Hub-and-spoke architecture for hybrid networks.  

### **Module 2: Hybrid & Global Networking**  
🛠️ **Skills**: Connect on-premises to AWS, optimize global traffic.  
4. **VPN & Direct Connect**  
   - Site-to-Site VPN vs. AWS Direct Connect.  
5. **Route 53 Advanced Routing**  
   - Latency-based, geolocation, and failover routing.  
6. **Global Accelerator**  
   - Improve performance with static Anycast IPs.  

### **Module 3: Security Hardening**  
🛠️ **Skills**: Protect apps from exploits, encrypt data.  
7. **Network Firewall & WAF**  
   - Layer 7 filtering, block SQLi/XSS attacks.  
8. **KMS Encryption**  
   - Manage keys for S3, EBS, RDS.  

### **Module 4: Scalability**  
🛠️ **Skills**: Design fault-tolerant, auto-scaling systems.  
9. **Load Balancers (ALB/NLB)**  
   - Path-based routing, static IPs.  
10. **Auto Scaling Policies**  
    - Scale EC2 based on CPU/memory.  

### **Phase 2 Final Project**  
🎯 **Multi-Region 3-Tier Architecture**  
- Web (ALB + WAF), App (private subnets), DB (Multi-AZ RDS).  
- Deploy with Global Accelerator.  

---

## 🗂️ Phase 3: DevOps, Automation & Enterprise Governance  
*(For aspiring AWS architects/DevOps engineers)*  

### **Module 1: Infrastructure as Code (IaC)**  
🛠️ **Skills**: Automate deployments at scale.  
1. **Advanced CloudFormation**  
   - Nested stacks, custom resources.  
2. **Terraform Basics**  
   - Deploy a VPC with Terraform.  

### **Module 2: Containers & Serverless**  
🛠️ **Skills**: Run microservices on AWS.  
3. **EKS (Managed Kubernetes)**  
   - Deploy a cluster with node groups.  
4. **AWS Lambda & API Gateway**  
   - Serverless REST APIs with JWT auth.  

### **Module 3: Monitoring & CI/CD**  
🛠️ **Skills**: Monitor apps, automate deployments.  
5. **CloudWatch & SNS**  
   - Custom dashboards, alerts.  
6. **CI/CD Pipelines**  
   - Blue/green deployments with CodePipeline.  

### **Module 4: Enterprise Governance**  
🛠️ **Skills**: Manage multi-account environments.  
7. **AWS Organizations**  
   - SCPs for compliance.  
8. **Cost Optimization**  
   - Reserved Instances, Savings Plans.  

### **Phase 3 Final Project**  
🎯 **End-to-End Serverless Microservices**  
- Frontend (S3 + CloudFront), Backend (Lambda + DynamoDB).  
- CI/CD pipeline with CodePipeline.  

---

## 🛠️ Getting Started  
1. **Prerequisites**:  
   - A computer + internet connection.  
   - [AWS Free Tier Account](https://aws.amazon.com/free/).  
2. **Clone the Repo**:  
   ```bash
   git clone https://github.com/kala-techies/AWS-Admin-Handbook.git
   ```  
3. **Run Labs**:  
   - Follow module guides and check the `labs/` folder for code.  

---

## 🤝 Contribute & Connect  
- **Found a bug?** Open an [issue](https://github.com/kala-techies/AWS-Admin-Handbook/issues).  
- **Add a lab?** Read [CONTRIBUTIONS.md](CONTRIBUTIONS.md) and submit a PR!  
- **Say Hi**: [connectwithkala18@gmail.com](mailto:connectwithkala18@gmail.com)  

---

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) 
[![Code of Conduct](https://img.shields.io/badge/Contributor%20Covenant-2.1-4baaaa.svg)](CODEOFCONDUCT.md)
