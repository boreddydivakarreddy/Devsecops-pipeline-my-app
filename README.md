# 🚀 DevSecOps CI/CD Pipeline with Security Scanning

## 📌 Project Overview
This project implements an end-to-end DevSecOps pipeline using GitHub Actions, Docker, AWS ECR, and EC2.

It automates:
- Build → Scan → Push → Deploy

---

## 🏗️ Architecture

Developer → GitHub → GitHub Actions → Docker Build → Trivy Scan → AWS ECR → EC2 Deployment

---

## 🛠️ Tech Stack

- AWS EC2
- AWS ECR
- Docker
- GitHub Actions
- Terraform (optional)
- Trivy (Security scanning)

---

## 🔐 Security Features

- Trivy vulnerability scanning
- Blocks CRITICAL vulnerabilities
- Secure AWS authentication

---

## ⚙️ CI/CD Pipeline Flow

1. Code pushed to GitHub
2. GitHub Actions triggers pipeline
3. Docker image built
4. Trivy scans image
5. Image pushed to AWS ECR
6. Application deployed to EC2

---

## 🐳 Docker Build

```bash
docker build -t my-app .
