# 🚀 Next.js CI/CD Pipeline using Jenkins & AWS EC2

This project demonstrates a **complete CI/CD workflow** for a **Next.js application** using **Jenkins** and **AWS EC2**.  
Whenever code is pushed to the Git repository, Jenkins automatically builds and deploys the application to an EC2 instance.

---

## 🧩 Tech Stack

- **Frontend**: Next.js (React)
- **Version Control**: Git & GitHub
- **CI/CD Tool**: Jenkins
- **Cloud Platform**: AWS EC2 (Ubuntu)
- **Web Server / Process Manager**: PM2 / Node.js
- **OS**: Ubuntu 22.04 LTS

---

## 🏗️ Architecture Overview

```text
Developer (Git Push)
        |
        v
GitHub Repository
        |
        v
Jenkins Pipeline
        |
        v
Build & Test Next.js App
        |
        v
Deploy to AWS EC2 Instance
        |
        v
Application Live 🚀
