🚀 Trend DevOps Project
🛠 Stack Used

React App

Docker & Docker Hub

AWS EKS (Kubernetes)

Jenkins (CI/CD)

Helm + Prometheus + Grafana (Monitoring)

Bash Scripting

GitHub CLI

📂 Output screenshots are available in the Trend folder.

📦 Project Setup

1️.Clone the App

git clone https://github.com/Vennilavan12/Trend.git

2️.Setup EC2 with Docker & Jenkins
3️.Dockerize the React App
4️. Setup EKS using eksctl
5️. Deploy App to Kubernetes

🔁 CI/CD Pipeline

Jenkins builds Docker image

Pushes to DockerHub

Deploys to Kubernetes cluster

Triggered automatically via GitHub webhook

📊 Monitoring Stack

1️.Create Monitoring Namespace

2️.Install Prometheus + Grafana

3️.Access Grafana Dashboard

🐳 Docker Hub Repos

Trend App DockerHub

☁️ AWS & Jenkins Access

EKS Cluster: trend-cluster in us-east-1

Jenkins on EC2: http://3.239.172.34:8080

Docker Image App on EC2: http://3.239.172.34:3000

App on EKS via LoadBalancer: http://a86ca331c710a4ffc9e0ab9781b12876-1228905747.us-east-1.elb.amazonaws.com:3000

🌟 The LoadBalancer exposes the app publicly from Kubernetes service.

