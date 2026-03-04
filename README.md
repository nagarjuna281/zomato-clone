# Zomato-Clone

## Credits & Original Source

This project was originally inspired by [devops0014/Zomato-Repo](https://github.com/devops0014/Zomato-Repo).  
It was initially forked and has since been restructured and customized into a standalone version.

Special thanks to the original author for laying the foundation.

# Zomato Clone – Secure CI/CD Pipeline

This project is a full-stack clone of the Zomato food delivery platform, enhanced with a secure CI/CD pipeline using Jenkins, Docker, Trivy, and SonarQube.

<img width="583" height="413" alt="2" src="https://github.com/user-attachments/assets/49f2f9ae-7c41-402a-a705-d9ae83a191df" />


## 🔐 Security-First DevOps Workflow

The pipeline includes:

- **Trivy File System Scan**: Detects vulnerabilities in local project files
- **Trivy Docker Image Scan**: Ensures container hygiene before deployment
- **SonarQube Analysis**: Enforces code quality and detects bugs
- **Docker Build & Push**: Automates image creation and pushes to DockerHub
- **Container Deployment**: Runs the app securely on a Docker container

## 🧠 What I Learned

- Implementing **DevSecOps principles** in a real-world Node.js project
- Using **Trivy** for vulnerability scanning at multiple layers
- Integrating **SonarQube** with Jenkins for continuous code quality checks
- Automating secure Docker workflows with Jenkins
- Handling pipeline failures gracefully and building for resilience

## 🚀 Technologies Used

- Node.js
- Jenkins
- Docker
- Trivy
- SonarQube
- GitHub

## 📦 How to Run

1. Clone the repo  
2. Set up Jenkins with required tools (Node.js, JDK, SonarQube scanner)  
3. Configure Docker and SonarQube credentials  

## 📁 Reports

- `trivyfs.txt`: File system vulnerability scan
- SonarQube dashboard: Code quality metrics

---
