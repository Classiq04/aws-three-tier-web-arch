# aws-three-tier-web-arch
<img width="1214" height="548" alt="AWS" src="https://github.com/user-attachments/assets/3fe080dc-8584-4815-8114-1b64f53d78f9" />

## 1. Project Overview & Goals

This project documents the successful, hands-on implementation of a production-ready **Three-Tier Web Application Architecture** on Amazon Web Services (AWS). This common industry pattern was established to ensure the application is highly available, scalable, and secure.

### Project Goals

* **Establish a Highly Available Infrastructure:** Deploy all critical services (VPC, EC2, RDS, ALB) across at least two **Availability Zones (AZs)** to ensure fault tolerance.
* **Implement Network Security:** Utilize **Security Groups** and **VPC Subnetting** to strictly control traffic flow between the Presentation, Application, and Data tiers.
* **Ensure Scalability:** Configure an **Application Load Balancer (ALB)** and **Auto Scaling Group (ASG)** to automatically handle traffic fluctuations and maintain application health.
* **Demonstrate Foundational AWS Skill:** Execute the entire build manually via the AWS Console, showcasing a strong understanding of core AWS services and architectural best practices.

### Key AWS Services Utilized

This implementation involved the configuration of the following core AWS services:

* **Networking:** VPC, Internet Gateway, NAT Gateway, Route Tables, Security Groups
* **Load Balancing & Scaling:** Application Load Balancer (ALB), Target Groups, Auto Scaling Group (ASG), Launch Templates
* **Compute:** EC2
* **Data Tier:** Amazon RDS (Relational Database Service - e.g., MySQL/Aurora)

---

### Now we move to Step 2: Implementation Details.

**Your First Task (Section 2.2):**

Let's write the introductory text for **Lab 1: VPC and Networking Setup**. This will be the first section after the "Project Overview."

**Draft your sentence describing the networking setup.** (e.g., "The network foundation was established by creating a custom VPC, six subnets across two AZs, and configuring NAT and Internet Gateways to manage traffic flow securely.")

Once you provide that line, we can dive into your screenshots and key configurations for VPC/Subnets.

