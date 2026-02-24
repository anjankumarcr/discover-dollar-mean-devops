# 🚀 MEAN Stack CRUD Application - DevOps Deployment

## 📌 Project Overview

This project demonstrates a full-stack CRUD (Create, Read, Update, Delete) application built using the **MEAN stack**:

- **MongoDB** – Database
- **Express.js** – Backend framework
- **Angular 15** – Frontend framework
- **Node.js** – Runtime environment

The application manages a collection of tutorials. Each tutorial contains:

- ID
- Title
- Description
- Published Status

Users can:
- ✅ Create tutorials
- 📄 Retrieve tutorials
- ✏ Update tutorials
- ❌ Delete tutorials
- 🔎 Search tutorials by title

---

## 🌍 Live Application

🔗 **Live URL:**  
http://65.1.134.40

🔗 **GitHub Repository:**  
https://github.com/anjankumarcr/discover-dollar-mean-devops

---

## 🏗 Architecture

User → Nginx (Frontend Container)  
Frontend → Backend (Node/Express Container)  
Backend → MongoDB Container  

CI/CD Flow:  
GitHub → Docker Build → DockerHub → AWS EC2 → Docker Compose

---

## 🛠 Tech Stack

### Frontend
- Angular 15
- TypeScript
- HTTPClient

### Backend
- Node.js
- Express.js
- REST APIs

### Database
- MongoDB

### DevOps Tools
- Docker
- Docker Compose
- GitHub Actions (CI/CD)
- AWS EC2
- DockerHub

---

## 🐳 Docker Setup

### Run Locally with Docker

```bash
docker-compose up --build
