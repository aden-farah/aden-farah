# Hi, I'm Aden 👋 
## IT Student | Cloud Infrastructure, DevOps & Automation

I'm an IT student at **OsloMet**, interested in **Cloud Infrastructure, DevOps and Automation**.

I like building projects to understand what happens beyond writing code: how applications are deployed, monitored and kept running. Most of my hands-on work so far has been with Azure, Docker, CI/CD and infrastructure as code.

Long term, I'd like to work in **Platform Engineering**, especially on internal developer platforms (IDPs) that make it easier for developers to build, deploy and run their applications.

💼 Open to internships and junior roles in Cloud and DevOps.

## 🚀 Projects

### 📊 System Status Dashboard

A Flask status dashboard monitored with Prometheus, Grafana, Node Exporter and cAdvisor, running in Docker Compose. Grafana dashboards and alert rules cover CPU, memory, disk usage, uptime and application metrics.

- **Pipeline:** GitHub Actions runs pytest, builds the Docker image, scans it with Trivy (the build fails on serious findings) and pushes it to GHCR
- **Infrastructure:** provisioned on Azure with Terraform, with SSH-key-only access and a scoped network security group
- **Deployment:** GitHub Actions authenticates to Azure with OIDC, so no long-lived secrets are stored in the repo

**Stack:** `Python` `Flask` `Docker Compose` `Prometheus` `Grafana` `Node Exporter` `cAdvisor` `Terraform` `Azure` `GitHub Actions` `Trivy`

📂 **[View repository](https://github.com/aden-farah/system-status-dashboard)**

### 🔗 URL Shortener

A URL shortening service built with **FastAPI and PostgreSQL**, running locally with Docker Compose and a persistent database volume. I'm using it to go from a working application to an automated cloud deployment, doing the infrastructure work step by step.

**Stack:** `Python` `FastAPI` `PostgreSQL` `Docker` `GitHub Actions`

**Next:** `Terraform` → `Azure deployment` → `Monitoring` → `Security scanning` → `AKS`

📂 **[View repository](https://github.com/aden-farah/url-shortener-cicd)**

### 🌐 Personal Portfolio

My personal website, hosted on Azure Static Web Apps and deployed through GitHub Actions.

**Stack:** `HTML` `CSS` `JavaScript` `Azure` `GitHub Actions`

🌍 **[adenfarah.no](https://adenfarah.no)**

---

## 🛠️ Tools & Technologies

### ☁️ Cloud & Infrastructure

![Azure](https://img.shields.io/badge/Azure-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-844FBA?style=for-the-badge&logo=terraform&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)

### 🔄 CI/CD & Observability

![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white)

### 💻 Languages & Databases

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)

---

## 📚 Currently Learning

I'm learning more about **Kubernetes, Linux and cloud infrastructure**, with the goal of eventually moving my projects to **Azure Kubernetes Service (AKS)**.

## 🤝 Connect

🌐 [Portfolio](https://adenfarah.no)  
💼 [LinkedIn](https://www.linkedin.com/in/aden-farah/)  
📧 [Email](mailto:aden.farah.dev@gmail.com)
