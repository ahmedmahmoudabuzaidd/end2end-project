<!-- Banner Image at the very top -->
![End-to-End DevOps Project Banner](./9105d737-4bb6-4884-87b3-4b6bfb741ffd.png)

# End-to-End DevOps Project 🚀

This project demonstrates a complete **DevOps pipeline** from code to deployment, monitoring, and end-user delivery.  
It integrates multiple tools and technologies to automate the workflow for developers, ensuring **quality, reliability, and continuous delivery**.

---

## 🖥 Project Overview

This project implements an end-to-end workflow:

1. **Developers** push code to **GitHub**.
2. **Jenkins** builds and tests the code automatically.
3. **SonarQube** performs code quality analysis.
4. **Docker** containerizes the applications.
5. **Trivy** scans Docker images for vulnerabilities.
6. Applications are deployed to a **Kubernetes cluster**.
7. **Prometheus** collects metrics and **Grafana** visualizes them.
8. Notifications are sent via **Gmail** to stakeholders.
9. **End Users** interact with the deployed applications.

---

## 🛠 Tech Stack & Tools

![GitHub](https://img.shields.io/badge/GitHub-181717?logo=github&logoColor=white&style=for-the-badge)
![Jenkins](https://img.shields.io/badge/Jenkins-D24939?logo=jenkins&logoColor=white&style=for-the-badge)
![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white&style=for-the-badge)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?logo=kubernetes&logoColor=white&style=for-the-badge)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?logo=prometheus&logoColor=white&style=for-the-badge)
![Grafana](https://img.shields.io/badge/Grafana-F46800?logo=grafana&logoColor=white&style=for-the-badge)
![Trivy](https://img.shields.io/badge/Trivy-3EAAAF?style=for-the-badge)
![SonarQube](https://img.shields.io/badge/SonarQube-4E9BCD?logo=sonarqube&logoColor=white&style=for-the-badge)
![Gmail](https://img.shields.io/badge/Gmail-D14836?logo=gmail&logoColor=white&style=for-the-badge)

---

## 📊 Workflow Diagram

![End-to-End DevOps Workflow](./9105d737-4bb6-4884-87b3-4b6bfb741ffd.png)

**Workflow Steps:**

```mermaid
flowchart TD
    A[Developer pushes code to GitHub] --> B[Jenkins builds & tests code]
    B --> C[SonarQube analyzes code quality]
    C --> D[Docker containerizes application]
    D --> E[Trivy scans for vulnerabilities]
    E --> F[Kubernetes deploys application]
    F --> G[Prometheus collects metrics]
    G --> H[Grafana visualizes metrics]
    H --> I[Stakeholders receive Gmail notifications]
    I --> J[End Users access the deployed application]
