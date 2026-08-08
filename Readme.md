Welcome to Devops Full end-to-end flow of the project
# 🛠️ Prerequisites

This project is developed and tested on Windows 11 using Docker Desktop and
WSL2.

## 💻 Operating System

- Windows 11
- WSL2
- Ubuntu via WSL2

## 🔧 Required Tools

| Tool | Version | Purpose |
|---|---|---|
| Git | 2.55.0.windows.3 | Source control |
| Docker | 29.6.2 | Containerization |
| Docker Compose | v5.3.1 | Multi-container orchestration |
| Kubernetes CLI (kubectl) | v1.36.1 | Kubernetes management |
| Kustomize | v5.8.1 | Kubernetes configuration |
| Terraform | v1.15.8 | Infrastructure as Code |
| AWS CLI | 2.36.8 | AWS management |
| eksctl | 0.229.0 | Amazon EKS management |
| Java | 21.0.12 LTS | Java/Spring Boot development |
| Jenkins | Installed | CI/CD automation |
| ArgoCD | Planned | GitOps deployment |

> Versions may differ slightly depending on the environment. The versions
> above represent the development environment used for this project.
>

Clone of the Repo: git clone https://github.com/Ananyakulshrestha123/cloud-native-devsecops-pipeline.git
To verify : git --version
docker --version
docker compose version
kubectl version --client
terraform version
aws --version
eksctl version
java -version

Expected :
Git                 2.55.0.windows.3
Docker              29.6.2
Docker Compose      v5.3.1
kubectl             v1.36.1
Terraform           v1.15.8
AWS CLI             2.36.8
eksctl              0.229.0
Java                21.0.12 LTS

Application flow of the project
1. Install required tools
          ↓
2. Clone GitHub repository
          ↓
3. Configure environment variables
          ↓
4. Run Docker Compose locally
          ↓
5. Test application
          ↓
6. Configure AWS CLI
          ↓
7. Provision infrastructure with Terraform
          ↓
8. Create/connect Amazon EKS
          ↓
9. Deploy Kubernetes resources
          ↓
10. Configure Jenkins CI/CD
          ↓
11. Push Docker images to ECR
          ↓
12. Configure ArgoCD
          ↓
13. Enable GitOps deployment
          ↓
14. Configure Prometheus
          ↓
15. Configure Grafana
          ↓
16. Monitor application

Jenkins CD Pipeline
GitHub
   |
   v
Jenkins
   |
   +--> Checkout
   |
   +--> Install Dependencies
   |
   +--> Build
   |
   +--> Unit Tests
   |
   +--> Code Quality Checks
   |
   +--> Security Scanning
   |
   +--> Docker Image Build
   |
   +--> Push Image
