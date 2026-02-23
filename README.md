This version is designed to be visually striking, easy to scan, and optimized for hiring managers who may only spend 30 seconds looking at your repository. It uses professional formatting, clear hierarchy, and industry-standard documentation practices.

---

# 🚗 Vehicle Data ML-Ops Pipeline

> **A Production-Grade End-to-End Machine Learning Ecosystem**

<br />

## 🌟 Project Overview

Handling machine learning models in a notebook is easy; bringing them into production is where the challenge lies. This project solves the **"Deployment Gap"** by building a fully automated **ML-Ops Pipeline**.

From the moment data hits the **MongoDB** database to its final deployment as a **Dockerized container on AWS**, every step—ingestion, validation, transformation, and evaluation—is code-driven and automated.

---

## 🛠 Tech Stack

| Layer | Technologies |
| --- | --- |  
| **Language** | 'python' |
| **Data Storage** |  |
| **Infrastructure** |  |
| **DevOps** |  |
| **ML Libraries** | `Scikit-learn`, `Pandas`, `XGBoost`, `EvidentlyAI` |

---

## 🏗 System Architecture & Workflow

The pipeline is designed with a **Modular Component Architecture**, ensuring high maintainability and scalability.

### **The Pipeline Flow:**

1. **Data Ingestion:** Securely pulls raw vehicle data from MongoDB Atlas.
2. **Data Validation:** Checks for schema consistency and data drift using a predefined YAML schema.
3. **Data Transformation:** Automates feature engineering and handles class imbalances.
4. **Model Trainer:** Trains the model and exports artifacts (Pickle files).
5. **Model Evaluation:** Compares the "Candidate" model with the "Production" model stored in **AWS S3**.
6. **Model Pusher:** If the candidate model is better (threshold > 2%), it is automatically pushed to the **S3 Model Registry**.

---

## 📂 Project Structure

```bash
├── .github/workflows   # 🚀 CI/CD pipeline definitions
├── src/                # 💻 Core source code
│   ├── components      # Data Ingestion -> Model Pusher
│   ├── entity          # Configuration and Artifact schemas
│   ├── pipeline        # Training & Prediction logic
│   └── utils           # Helper functions (AWS/S3/MongoDB)
├── static/             # 🎨 UI CSS and JS
├── templates/          # 📄 HTML Web Interfaces
├── Dockerfile          # 🐳 Containerization instructions
└── app.py              # 🔌 Flask/FastAPI Gateway

```

---

## 🚀 Installation & Local Setup

### **1. Environment Setup**

```bash
# Clone the repository
git clone https://github.com/your-username/vehicle-mlops.git

# Create and Activate Environment
conda create -n vehicle python=3.10 -y
conda activate vehicle

# Install dependencies
pip install -r requirements.txt

```

### **2. Set Secret Keys**

```bash
# Mac/Linux
export MONGODB_URL="your_mongodb_connection_string"
export AWS_ACCESS_KEY_ID="your_aws_key"
export AWS_SECRET_ACCESS_KEY="your_aws_secret"

# Windows (Powershell)
$env:MONGODB_URL="your_mongodb_connection_string"

```

---

## 📈 Results & Performance

* **Model Performance:** Achieved an F1-Score of **0.XX** on validation sets.
* **Automation:** Reduced deployment time from hours to **under 5 minutes** via CI/CD.
* **Reliability:** Implemented automated data validation, reducing "Garbage In, Garbage Out" risks.

---

## 💡 Key Engineering Highlights (Placement Ready)

* **Scalable Codebase:** Used "Entity-Component" design patterns for clean, production-grade code.
* **Cloud Native:** Integrated AWS S3 for model versioning and ECR for container management.
* **CI/CD Proficiency:** Established a self-hosted runner on EC2 for secure, automated deployments.
* **Containerization:** Utilized Docker to eliminate the "it works on my machine" problem.

---

## 👨‍💻 Author

**Narottam Kumar** *Computer Science & Engineering | MMMUT Gorakhpur* [](https://www.linkedin.com/in/narottam-kumar-a16a04293/)
[](https://github.com/Narottam-kumar12)
