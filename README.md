# CI/CD Pipeline - Task 1

A simple Node.js application with an automated CI/CD pipeline using GitHub Actions and Docker.

## 🛠️ Technologies Used

- Node.js
- Express.js
- GitHub
- GitHub Actions
- Docker
- Docker Hub

## 📌 Project Overview

This project demonstrates a basic CI/CD pipeline that automatically:

1. Installs Node.js dependencies
2. Runs automated tests
3. Builds a Docker image
4. Pushes the Docker image to Docker Hub

The pipeline is triggered whenever code is pushed to the `main` branch.

## 🔄 CI/CD Pipeline

```text
Git Push
   ↓
GitHub Actions
   ↓
Install Dependencies
   ↓
Run Tests
   ↓
Build Docker Image
   ↓
Push Image to Docker Hub
