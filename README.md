# SmartCityOps
Real-Time Infrastructure Monitoring and Auto-Healing System for Smart Cities using Kubernetes, Terraform, Prometheus, Grafana, and GitOps.


# SmartCityOps

🚦 Real-Time Infrastructure Monitoring & Auto-Healing System for Smart Cities.

## 🔧 Tech Stack

- Kubernetes (EKS)
- Terraform (IaC)
- Prometheus & Grafana (Monitoring)
- Argo CD & Argo Rollouts (GitOps & Auto-healing)
- Python AI module (anomaly detection)
- AWS (Cloud Infra)

## 📁 Project Structure


SmartCityOps/
│
├── infrastructure/ # Terraform: VPC, EKS
├── k8s/ # Kubernetes YAMLs
├── monitoring/ # Prometheus & Grafana setup
├── ai/ # Anomaly detection logic
└── docs/ # Architecture diagrams, notes




## 🌍 Objective

To build a smart monitoring system for public infrastructure (air sensors, power units, traffic lights) that detects real-time anomalies and fixes them automatically using AI + GitOps automation.

## 💡 How it works

1. Terraform deploys AWS infrastructure (VPC, EKS).
2. Prometheus scrapes metrics from sensor simulators.
3. Grafana visualizes sensor health in real time.
4. Anomaly detection AI flags suspicious patterns.
5. Alerts trigger GitOps pipelines (Argo Rollouts) to fix problems.

