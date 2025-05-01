# 🚀 CI/CD Pipeline with GitHub Actions and Docker (Local Deployment)

This project demonstrates a complete CI/CD pipeline setup using **GitHub Actions** and **Docker** to automate the build and deployment of a Flask web application — all running on a **local machine or self-hosted server**. No cloud-specific CI/CD tools are used, making it ideal for learning DevOps fundamentals locally.

---

## ✅ Features

- 🐍 Flask-based Python web application
- 🔁 End-to-end CI/CD pipeline with GitHub Actions
- 🐳 Docker containerization and deployment
- ⚡ Triggered on push to `main` branch
- 🖥️ Runs entirely on local or self-hosted environments

---

## 🧰 Tech Stack

- Python 3.10
- Flask
- GitHub Actions
- Docker
- Git
- Ubuntu or Windows (for testing)

## ![Screenshot 2025-04-26 133037](https://github.com/user-attachments/assets/d86bf901-03b0-495c-b1ca-bd4d14b83a5e)
![Screenshot 2025-04-26 132229](https://github.com/user-attachments/assets/c10a0071-e940-4b7e-8573-1f02d430bf48)
📌 How It Works
Developer pushes code to GitHub main branch.

GitHub Actions is triggered.

Python is set up and dependencies are installed.

Docker image is built from the latest code.

Optionally deploy/run the app from the container.
