# AWS Cloud Infrastructure and Web Hosting

A hands-on cloud infrastructure project demonstrating the deployment and administration of Linux servers on Amazon Web Services (AWS). This project focuses on provisioning cloud resources, securing access, hosting web applications, and documenting deployment procedures following infrastructure best practices.

---

## Project Overview

This project demonstrates the process of deploying and managing a Linux-based web server using AWS EC2. It covers core cloud administration concepts including instance provisioning, Identity and Access Management (IAM), Security Groups, SSH connectivity, and web server configuration using Nginx.

The project is designed to develop practical cloud infrastructure skills relevant to System Engineer, Cloud Support Engineer, Infrastructure Engineer, and Technical Support roles.

---

## Project Status

| Module              | Status         |
| ------------------- | -------------- |
| AWS Account Setup   | ✅ Completed    |
| EC2 Instance Launch | 🔄 In Progress |
| SSH Configuration   | ⏳ Planned      |
| Security Groups     | ⏳ Planned      |
| IAM Configuration   | ⏳ Planned      |
| Nginx Installation  | ⏳ Planned      |
| Website Deployment  | ⏳ Planned      |
| Documentation       | ✅ Completed    |

---

## Technologies Used

* Amazon Web Services (AWS)
* Amazon EC2
* IAM
* Security Groups
* Ubuntu Linux
* Nginx
* SSH

---

## Skills Demonstrated

* Cloud Infrastructure Deployment
* Linux Server Administration
* EC2 Instance Management
* Identity and Access Management (IAM)
* Network Security Configuration
* Remote Server Administration
* Web Server Deployment
* Infrastructure Documentation

---

## Architecture

```text
                Internet
                    │
                    ▼
            AWS Security Group
                    │
                    ▼
            EC2 Ubuntu Instance
                    │
          ┌─────────┴─────────┐
          │                   │
         SSH              Nginx Web Server
          │                   │
          ▼                   ▼
  Remote Administration   Hosted Website
```

---

## Project Structure

```text
aws-cloud-infrastructure-hosting/
│
├── README.md
├── architecture/
├── docs/
├── screenshots/
└── scripts/
```

---

## Implementation Steps

### EC2 Deployment

* Launch Ubuntu EC2 instance
* Configure key pair
* Assign Security Groups
* Connect using SSH

---

### Security Configuration

* Configure inbound rules
* Allow SSH (Port 22)
* Allow HTTP (Port 80)
* Restrict unnecessary access

---

### Linux Server Administration

* Update packages
* Install Nginx
* Manage services using Systemd
* Configure web root

---

### Website Deployment

* Deploy static website
* Verify public accessibility
* Monitor service status

---

## AWS Services Used

| Service         | Purpose                |
| --------------- | ---------------------- |
| EC2             | Virtual Server         |
| IAM             | Access Management      |
| Security Groups | Firewall Configuration |

---

## Screenshots

Screenshots will be added during project implementation.

Examples include:

* EC2 Dashboard
* Security Group Rules
* SSH Terminal
* Nginx Installation
* Hosted Website

---

## Learning Outcomes

Through this project, I gained practical experience in:

* Deploying Linux servers on AWS
* Configuring secure remote access
* Managing EC2 instances
* Implementing cloud security fundamentals
* Hosting web applications
* Documenting cloud deployments

---

## Future Enhancements

* Configure Elastic IP
* Add Route 53 Domain
* Configure HTTPS using SSL/TLS
* Deploy dynamic applications
* Automate deployment using Bash
* Explore Infrastructure as Code (Terraform)

---

## Author

**Tejas Pawar**

Aspiring System Engineer | Linux | AWS Cloud | Networking | Virtualization

---

## Connect

* GitHub: https://github.com/tsp0602
* LinkedIn: https://www.linkedin.com/in/pawar-tejas-mh17aw3217/
