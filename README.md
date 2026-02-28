# 🚀 Node.js CI/CD Pipeline on AWS

This project demonstrates an end-to-end CI/CD pipeline for a Node.js application deployed on AWS EC2 using GitHub Actions.

## 🏗 Architecture
- AWS EC2 (Amazon Linux 2023)
- Node.js + Express
- PM2 Process Manager
- GitHub Actions for CI/CD
- Secure SSH authentication using GitHub Secrets

## ⚙️ CI/CD Workflow
- Triggered on push to `main` branch
- GitHub Actions connects to EC2 via SSH
- Pulls latest code
- Installs dependencies
- Restarts application using PM2

## 🔐 Security
- SSH Private Key stored securely in GitHub Secrets
- No hardcoded credentials

## 🚀 Outcome
Automatic deployment on every push to the main branch.

---

Built as a hands-on DevOps learning project.
