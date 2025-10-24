# Terraform AWS Infrastructure Project

## 🧭 Overview
This project automates the provisioning of AWS infrastructure using Terraform.  
It creates a **VPC**, **Public & Private Subnets**, **EC2 Instance**, and **RDS MySQL Database**.

---

## 🏗️ Architecture

- **VPC**: 10.0.0.0/16
- **Public Subnet**: 10.0.1.0/24 (for EC2)
- **Private Subnet**: 10.0.2.0/24 (for RDS)
- **EC2**: Hosts Nginx web server
- **RDS MySQL**: Private DB accessible only via EC2

---

## ⚙️ Tech Stack
- **Terraform** v1.5+
- **AWS** (VPC, EC2, RDS, Subnets, Security Groups)
- **Amazon Linux 2**

---

## 🚀 How to Deploy


terraform init
terraform plan
terraform apply -auto-approve
