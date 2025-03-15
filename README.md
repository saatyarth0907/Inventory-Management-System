# **Inventory Management System - DevOps Project**

## **📌 Project Overview**
The **Automated Inventory Management System** is a cloud-based inventory tracking system designed to automate inventory updates, orders, and stock level management using **AWS CodePipeline, Terraform, and CI/CD practices**.

### **🚀 Key Features**
✅ **Automated Inventory Updates** - Dynamically updates stock levels after orders.

✅ **Order Processing System** - Tracks orders and reduces stock accordingly.

✅ **CI/CD Pipeline** - Uses AWS CodePipeline for automated deployments.

✅ **Infrastructure as Code (IaC)** - Terraform is used for cloud infrastructure provisioning.

✅ **Monitoring & Logging** - Uses Prometheus, Grafana, and AWS CloudWatch for real-time tracking.

✅ **Security Implementation** - Integrated SonarQube, OWASP ZAP for vulnerability scanning.

---

## **🛠️ Tech Stack & Tools Used**
### **Frontend & Backend:**
- **HTML, CSS, JavaScript** (for UI & functionality)

### **DevOps & Cloud Services:**
- **AWS CodePipeline** (CI/CD pipeline)
- **AWS ECS (Fargate) / EC2** (Deployment infrastructure)
- **AWS S3** (Artifact storage)
- **Terraform** (Infrastructure automation)
- **GitHub Actions** (Optional CI/CD integration)

### **Monitoring & Security:**
- **AWS CloudWatch** (Application logs)
- **SonarQube & OWASP ZAP** (Security testing)

---

## **🔧 Project Setup & Installation**

### **1️⃣ Clone the Repository**
```sh
git clone https://github.com/saatyarth0907/inventory-management.git
cd inventory-management
```

### **2️⃣ Install Dependencies**
```sh
npm install  # Install backend dependencies
```

### **3️⃣ Start the Development Server**
```sh
npm start  # Start backend
```

### **4️⃣ Configure AWS Infrastructure (Terraform Deployment)**
```sh
terraform init   # Initialize Terraform
terraform plan   # Preview infrastructure changes
terraform apply  # Deploy infrastructure to AWS
```

---

## **⚙️ CI/CD Pipeline Workflow**
### **1️⃣ GitHub Actions (Alternative CI/CD)**
- **Push to GitHub** triggers **AWS CodePipeline**
- **CodeBuild** compiles and tests the application
- **CodeDeploy** pushes to **ECS (Fargate) or EC2**

### **2️⃣ Manual Deployment with Terraform**
- Define infrastructure using Terraform
- Run Terraform apply to deploy services

---

## **📊 Monitoring & Security**
- **AWS CloudWatch & Grafana** for real-time log tracking
- **Prometheus** for server health monitoring
- **SonarQube & OWASP ZAP** for security scans

---

## **📂 Project Structure**
```
├── src/                 # Source code (backend + frontend)
├── terraform/           # Infrastructure as Code (Terraform configs)
├── scripts/             # Deployment & automation scripts
├── README.md            # Documentation
├── package.json         # Node.js project dependencies
├── .github/workflows/   # CI/CD pipeline configuration (GitHub Actions)
```

---

## **📅 Roadmap & Future Enhancements**
- **Auto-scaling & Load Balancing** using AWS ALB
- **Database Migration & Optimization** (AWS RDS / DynamoDB)
- **Machine Learning for Demand Forecasting** (AWS SageMaker)

---

## **👨‍💻 Contributors**
👤 **[Satyarth]** - Project Lead  

---

## **📜 License**
This project is licensed under the **MIT License**.

---

## **📞 Contact & Support**
- 🔗 GitHub Issues: [https://github.com/saatyarth0907/inventory-management/issues]

