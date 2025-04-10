# Task 3: Infrastructure as Code with Terraform 🛠️

## 📌 Objective
Provision a local Docker container using Terraform to understand Infrastructure as Code (IaC).

## 🧰 Tools Used
- Terraform
- Docker
- WSL Ubuntu

## 🚀 What I Did
- Installed Docker & Terraform in WSL
- Created `main.tf` to:
  - Pull nginx image
  - Deploy container on port 8080
- Verified Nginx on http://localhost:8080
- Ran `terraform init`, `plan`, `apply`, `state list`, `destroy`

## 📂 Files
- `main.tf`
- `terraform.tfstate`
- `README.md`
- (Screenshots coming soon...)

## ✅ Status
Terraform successfully deployed an Nginx container. IaC working as expected ✅
