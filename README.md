# 🚀 CloudMart – AI-Powered E-Commerce Platform

CloudMart is an AI-integrated e-commerce platform that delivers intelligent product recommendations, seamless order management, and real-time customer support. It leverages cloud-native technologies across **AWS**, **Google Cloud**, **Azure**, and **OpenAI** to create a highly scalable and intelligent shopping experience.

---

## 📌 Project Summary

CloudMart integrates:
- **Amazon Bedrock + OpenAI** for product recommendations and AI-powered chat support
- **AWS Lambda & DynamoDB** for serverless backend
- **BigQuery** for analytics on historical data
- **Azure Text Analytics** for sentiment analysis
- **Kubernetes** for containerized frontend and backend deployment

---

## 🛠️ Tools & Services Used

### 1️⃣ AWS

- **AWS Lambda** – Serverless backend functions
- **Amazon DynamoDB** – NoSQL database for orders, products, and tickets
- **Amazon Bedrock (Claude 3 Sonnet)** – Product recommendation & support agent
- **AWS IAM** – Role-based access control
- **AWS ECR** – Stores container images
- **AWS CloudWatch** – Lambda log monitoring
- **AWS S3** – Hosting/static file storage
- **AWS API Gateway** – REST API gateway for frontend/backend communication
- **Terraform** – Infrastructure as Code for provisioning resources

### 2️⃣ Google Cloud

- **BigQuery** – Historical order data storage and analytics
- **Google Cloud Service Account** – Authentication for BigQuery operations
- **bq CLI** – Manage datasets/tables via CLI

### 3️⃣ Azure

- **Azure Text Analytics** – Sentiment analysis on customer reviews and chats

### 4️⃣ Kubernetes & DevOps

- **Kubernetes (EKS/K3s)** – Manages frontend & backend microservices
- **kubectl** – CLI for Kubernetes deployments
- **Docker** – Containerizes backend & frontend services

### 5️⃣ OpenAI

- **GPT-4o API** – Chatbot support for customer queries and engagement

---

## 📦 Folder Structure

```bash
.
├── src/                   # Frontend source code
├── public/                # Public assets
├── Dockerfile             # Container setup
├── .env                   # Environment variables
├── vite.config.js         # Frontend build config
├── terraform/             # Infra-as-Code (optional)
└── README.md              # This file
