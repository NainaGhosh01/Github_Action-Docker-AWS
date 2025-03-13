
# AWS CI/CD(GitHub Actions) Pipeline for Dockerized Web App

## Overview
This project automates the deployment of a **Dockerized web application** using **GitHub Actions, AWS Elastic Beanstalk, and Amazon ECR**.  

## Project Workflow  
- **Push Code to GitHub**: Triggers GitHub Actions  
- **GitHub Actions Builds & Pushes Docker Image**: Amazon ECR 
- **GitHub Actions Deploys Application**: AWS Elastic Beanstalk
- **Application is Live**: Elastic Beanstalk  

## Technologies Used  
- **GitHub Actions** – Automates deployment  
- **Docker** – Containerizes the application  
- **Amazon ECR** – Stores Docker images  
- **AWS Elastic Beanstalk** – Hosts the application 

## 🚀 How to Use  
### 1️⃣ **Setup AWS Credentials in GitHub**  
Go to **GitHub Repository** → **Settings** → **Secrets and variables** → **Actions** and add:  
- `AWS_ACCESS_KEY_ID`  
- `AWS_SECRET_ACCESS_KEY`  

### 2️⃣ **Push Code to GitHub**  
Every push to `main` triggers deployment **automatically**.

### 3️⃣ **Check Deployment Status**  
- Open **AWS Elastic Beanstalk Console** → **Your Environment**  
- Find your app running at:  

