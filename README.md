
# 🚀 Vehicle Insurance Risk Prediction System

### Production-Grade End-to-End MLOps Pipeline with AWS, Docker & CI/CD

---

![Python](https://img.shields.io/badge/Python-3.10-blue)
![Machine Learning](https://img.shields.io/badge/Machine-Learning-orange)
![MLOps](https://img.shields.io/badge/MLOps-Production-green)
![AWS](https://img.shields.io/badge/AWS-Cloud-yellow)
![Docker](https://img.shields.io/badge/Docker-Containerized-blue)
![CI/CD](https://img.shields.io/badge/CI/CD-GitHub%20Actions-black)
![MongoDB](https://img.shields.io/badge/MongoDB-Database-green)
![Status](https://img.shields.io/badge/Status-Production%20Ready-success)

---

## 📌 Overview

This project is a **production-ready, end-to-end Machine Learning system** designed to predict vehicle insurance risk using modern **MLOps architecture and cloud deployment**.

The system automates the complete ML lifecycle — from **data ingestion to model deployment and real-time prediction**, following industry standards used in large-scale ML systems.

It demonstrates strong expertise in:

• Machine Learning Engineering
• MLOps and CI/CD
• Cloud Deployment (AWS)
• Production-level system design

---

## 🧠 Business Problem

Insurance providers need to identify high-risk customers to:

• Reduce claim losses
• Improve risk assessment
• Optimize premium pricing
• Prevent fraud

Manual analysis is slow and inefficient.

This system automates the process using Machine Learning.

---

## 🏗️ System Architecture

```
                    ┌────────────────────┐
                    │   MongoDB Atlas    │
                    │   (Cloud Data)    │
                    └─────────┬──────────┘
                              │
                              ▼
                    ┌────────────────────┐
                    │ Data Ingestion     │
                    └─────────┬──────────┘
                              │
                              ▼
                    ┌────────────────────┐
                    │ Data Validation    │
                    └─────────┬──────────┘
                              │
                              ▼
                    ┌────────────────────┐
                    │ Data Transformation│
                    └─────────┬──────────┘
                              │
                              ▼
                    ┌────────────────────┐
                    │ Model Trainer      │
                    └─────────┬──────────┘
                              │
                              ▼
                    ┌────────────────────┐
                    │ Model Evaluation   │
                    └─────────┬──────────┘
                              │
                              ▼
                    ┌────────────────────┐
                    │ AWS S3 Model Store│
                    └─────────┬──────────┘
                              │
                              ▼
                    ┌────────────────────┐
                    │ Prediction Pipeline│
                    └─────────┬──────────┘
                              │
                              ▼
                    ┌────────────────────┐
                    │ Flask Web App     │
                    └─────────┬──────────┘
                              │
                              ▼
                    ┌────────────────────┐
                    │ Docker Container  │
                    └─────────┬──────────┘
                              │
                              ▼
                    ┌────────────────────┐
                    │ AWS EC2 Deployment│
                    └────────────────────┘
```

---

## ⚙️ Key Features

### ✔ End-to-End ML Pipeline

• Automated training pipeline
• Modular architecture
• Artifact tracking
• Reproducible workflows

### ✔ Cloud-Native Deployment

• AWS EC2 deployment
• AWS S3 model registry
• MongoDB Atlas integration

### ✔ CI/CD Automation

• GitHub Actions pipeline
• Automatic Docker build
• Automated deployment

### ✔ Production-Ready Design

• Logging system
• Exception handling
• Config-driven pipeline
• Scalable architecture

### ✔ Real-Time Prediction

• FlastApi web application
• REST-based prediction system

---

## 🛠️ Technology Stack

### Programming

• Python
• Flask

### Machine Learning

• Scikit-learn
• Pandas
• NumPy

### Database

• MongoDB Atlas

### Cloud

• AWS EC2
• AWS S3
• AWS ECR

### MLOps Tools

• Docker
• GitHub Actions
• CI/CD

---

## 📂 Project Structure

```
.
├── src/
│   ├── components/
│   ├── configuration/
│   ├── data_access/
│   ├── entity/
│   ├── pipeline/
│   ├── aws_storage/
│   ├── utils/
│   ├── logger/
│   └── exception/
│
├── notebook/
├── templates/
├── static/
├── artifact/
├── app.py
├── demo.py
├── Dockerfile
├── requirements.txt
├── setup.py
└── pyproject.toml
```

---

## 🔄 CI/CD Pipeline

```
Developer Push Code
        │
        ▼
GitHub Actions Triggered
        │
        ▼
Docker Image Build
        │
        ▼
Push to AWS ECR
        │
        ▼
Deploy on AWS EC2
        │
        ▼
Application Live
```

---

## 🐳 Docker Deployment

Build Docker image:

```bash
docker build -t vehicle-insurance .
```

Run container:

```bash
docker run -p 8000:8000 vehicle-insurance
```

---

## ☁️ AWS Deployment

Services used:

• AWS EC2 → Application hosting
• AWS S3 → Model storage
• AWS ECR → Docker image registry

---

## 🚀 Run Locally

### Clone Repository

```bash
git clone https://github.com/Narottam-kumar12/Vehicle-Insorance-MLOPs-Project.git
```

### Create Environment

```bash
conda create -n vehicle python=3.10 -y
conda activate vehicle
```

### Install Requirements

```bash
pip install -r requirements.txt
```

### Run Training

```bash
python demo.py
```

### Run Application

```bash
python app.py
```

---

## 🌐 Live Application

```
http://<EC2-PUBLIC-IP>:8000
```

---

## 📊 MLOps Best Practices Used

✔ Modular architecture
✔ Cloud model registry
✔ CI/CD automation
✔ Docker containerization
✔ Artifact management
✔ Logging and monitoring
✔ Reproducible pipelines

---

## 🎯 Skills Demonstrated

Machine Learning Engineering
MLOps Engineering
Cloud Deployment
System Design
CI/CD Pipeline Development

---

## 👨‍💻 Author

**Narottam Kumar**

B.Tech Computer Science Engineering
Machine Learning | MLOps | Data Science

GitHub:
[https://github.com/Narottam-kumar12](https://github.com/Narottam-kumar12)
