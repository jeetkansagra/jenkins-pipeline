# Spring Boot Java Web Application with Jenkins CI/CD Pipeline

![Pipeline Overview](https://user-images.githubusercontent.com/43399466/228301952-abc02ca2-9942-4a67-8293-f76647b6f9d8.png)

This repository contains a **Spring Boot based Java web application** and an **end-to-end Jenkins CI/CD pipeline** that automates building, testing, analyzing, containerizing, and deploying the application using **Maven, SonarQube, Helm, Argo CD, and Kubernetes**.

---

## 📌 Application Overview
- Simple Spring Boot MVC application  
- Built and packaged with Maven  
- Controller returns a page with `title` and `message` attributes  
- Can run locally or in a Docker container  

---

## 🧰 CI/CD Pipeline Overview
The pipeline automates the software delivery process for the application:  

1. Checkout code from GitHub  
2. Build with Maven  
3. Run Unit Tests (JUnit & Mockito)  
4. SonarQube Analysis for code quality  
5. Package JAR artifact  
6. Deploy to a test environment with Helm on Kubernetes  
7. Run User Acceptance Tests (optional)  
8. Promote to production with Argo CD  

---

## 🔧 Tools Used
- **Jenkins** – CI/CD automation  
- **Maven** – Build & dependency management  
- **JUnit/Mockito** – Testing  
- **SonarQube** – Code quality analysis  
- **Docker** – Containerization  
- **Helm** – Kubernetes packaging & deployment  
- **Argo CD** – GitOps-based deployment to Kubernetes  

---

## 🚀 Next Steps
- Configure and run a local SonarQube server (http://<ip>:9000)  
- Integrate Jenkins with Argo CD for automated deployments  
- Scale deployments on Kubernetes using Helm charts  

---

## ✅ Summary
This project demonstrates:  
- A working Spring Boot web application  
- An end-to-end Jenkins CI/CD pipeline with popular DevOps tools  
- Automated deployments to Kubernetes using GitOps best practices  
