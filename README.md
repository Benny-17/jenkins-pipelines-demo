# Jenkins Demo

This repository contains hands-on Jenkins pipeline projects demonstrating various CI/CD concepts using Jenkins, Docker, and GitHub integration.

### 📁 Structure

- `first-jenkins-file/`  
  A basic Jenkins pipeline that demonstrates a simple CI setup using a Docker container as the build agent. Ideal for understanding controller-agent architecture and Docker integration.

- `multi-stage | multi-build/`  
  A more advanced pipeline that uses different Docker containers for each stage (e.g., Maven for the backend, Node.js for the frontend). Demonstrates stage-specific agent usage and real-world pipeline design.

### 🛠️ Technologies Used

- Jenkins (standalone setup on EC2)
- Docker (as Jenkins build agent)
- Groovy (Jenkins Pipeline DSL)
- GitHub (for SCM and later webhook trigger)

### 🎯 Goals

To learn and demonstrate:
- Jenkins declarative pipeline syntax
- Controller-agent architecture (with Docker as agent)
- Multi-stage pipelines with isolated environments
- GitHub integration with Jenkins (manual and automated)

### ⚙️ Setup (applies to both folders)

- Jenkins installed on an EC2 instance (controller and agent in standalone mode)
- Docker installed and Jenkins user granted Docker daemon access
- Docker Pipeline plugin installed in Jenkins
- GitHub repository connected to Jenkins via webhook (for automation in future steps)
