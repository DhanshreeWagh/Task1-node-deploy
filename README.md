# Task 1: Automate Code Deployment Using CI/CD Pipeline (GitHub Actions)

This project demonstrates how to build and deploy a Node.js web application using GitHub Actions and Docker.

## 🚀 Tech Stack

- Node.js + Express – Simple web server
- Docker – Containerization
- GitHub Actions – Continuous Integration and Delivery
- Docker Hub – Image registry

---

## 📂 Project Structure
node-ci-cd-app/ ├── app.js # Main Node.js app ├── package.json # Dependencies and scripts ├── Dockerfile # Docker image build config └── .github/ └── workflows/ └── main.yml # GitHub Actions CI/CD workflow


---

yaml

## 🔁 Workflow Overview

The CI/CD pipeline performs the following steps automatically on every `push` to the `main` branch:

1. **Checkout Code** from GitHub
2. **Log in** to Docker Hub using secrets
3. **Build** Docker image of the Node.js app
4. **Push** image to Docker Hub

---


🧑‍💻 How to Use

1. Clone This Repository

    git clone https://github.com/DhanshreeWagh/Task1-node-deploy.git
    cd Task1-node-deploy

2.  Make a Code Change and Push:

     git add .
     git commit -m "Trigger CI/CD"
     git push origin main

3.  Docker Image

    Image is pushed to: docker.io/dhanshreewagh/task1-node-deploy:latest


Author:

Dhanshree Wagh

GitHub: @DhanshreeWagh


