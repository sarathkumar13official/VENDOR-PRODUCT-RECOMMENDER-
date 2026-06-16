# 🚀 Vendor Product Recommender

<img width="1536" height="1024" alt="VENDOR PRODUCT RECOMMENDER" src="https://github.com/user-attachments/assets/3e2e2ea5-f4df-44e7-9a31-045369cd07ad" />


A cloud-native vendor product recommendation system built with a Flask-based LLMOps workflow and deployed using Docker, Minikube, Kubernetes, Prometheus, and Grafana on Google Cloud Platform.

This project demonstrates an end-to-end workflow for building, deploying, and monitoring a recommendation application in a modern DevOps environment.

---

## 📌 Project Overview

Vendor Product Recommender is designed to help generate relevant product recommendations in a scalable and containerized environment. The application is packaged with Docker, deployed on a Kubernetes cluster running inside Minikube, and monitored using Prometheus and Grafana.

The project is structured to show a practical MLOps/LLMOps-style deployment pipeline from source control to cloud deployment and observability.

---

## 🧱 Architecture Flow

GitHub → Docker → Minikube → Kubernetes → Prometheus → Grafana

### Flow Explanation
- **GitHub** → Stores the source code, Dockerfile, and Kubernetes manifest files.
- **Docker** → Builds the application image.
- **Minikube** → Runs a local Kubernetes cluster on the VM.
- **Kubernetes** → Deploys and manages the application pods and services.
- **Prometheus** → Collects metrics from the application and cluster.
- **Grafana** → Visualizes performance and health metrics.

---

## ✨ Features

- Vendor product recommendation workflow.
- Dockerized application for consistent deployment.
- Kubernetes manifest-based deployment.
- Secret management for API keys and tokens.
- Minikube deployment on Google Cloud VM.
- Prometheus monitoring.
- Grafana dashboard visualization.
- GitHub integration for version control.

---

## 📁 Repository Structure

```bash
vendor-product-recommender/
├── Dockerfile
├── llmops-k8s.yaml
├── prometheus/
│   ├── prometheus-configmap.yaml
│   └── prometheus-deployment.yaml
├── grafana/
│   └── grafana-deployment.yaml
├── README.md
├── src/
└── requirements.txt
