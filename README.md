# AWS Infrastructure Automation using Terraform & GitLab CI/CD

This project demonstrates an end-to-end CI/CD pipeline that provisions AWS infrastructure using Terraform and deploys a Dockerized Nginx application on an EC2 instance.

## 🚀 Features
- Infrastructure provisioning using Terraform (VPC, Subnet, EC2, Security Groups)
- CI/CD automation using GitLab CI
- Secure SSH key generation using Terraform TLS provider
- Docker-based Nginx deployment
- Automated application testing
- Manual infrastructure teardown

## 🛠️ Tech Stack
- AWS (EC2, VPC, Security Groups)
- Terraform
- GitLab CI/CD
- Docker
- Linux

## 📂 Pipeline Stages
1. **Apply** – Provisions AWS infrastructure
2. **Deploy** – Deploys Dockerized Nginx to EC2
3. **Test** – Verifies application availability
4. **Destroy** – Manually destroys infrastructure

## 🔐 Security
- No hardcoded secrets
- SSH keys generated dynamically
- Artifact-based key handling across pipeline stages

## 📌 Usage
1. Configure AWS credentials as GitLab CI variables
2. Run pipeline
3. Access application via EC2 public IP

## 📸 Screenshots (Optional)
- GitLab pipeline success
- Nginx running in browser
