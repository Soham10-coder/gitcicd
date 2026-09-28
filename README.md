# 🚀 Docker + GitHub Actions CI/CD Pipeline

A complete CI/CD pipeline for a simple Apache website using **Docker, GitHub Actions, Docker Hub, and AWS EC2**.

---

## 📌 Project Overview

This project demonstrates how to automate the complete software delivery process:

```text
Developer
    │
    │ git push
    ▼
GitHub Repository
    │
    ▼
GitHub Actions
    │
    ├── Test
    │
    ├── Build Docker Image
    │
    ├── Dynamic Image Tag
    │
    ├── Push to Docker Hub
    │
    └── Deploy to AWS EC2
             │
             ▼
        Running Container
