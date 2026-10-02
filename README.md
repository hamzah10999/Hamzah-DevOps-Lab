# Hamzah-DevOps-Lab

A collection of hands-on DevOps exercises completed as part of the **DevOps** course.

## Student Details

| Field | Value |
|---|---|
| Name | Hamzah Ahmad |
| USN | 1BM23IS100 |
| Department | Information Science and Engineering (ISE) |
| Semester | 7th Semester |
| Faculty | Prof. Sunag P & Sumukha |
| Course | DevOps |

## About This Repository

This repository documents practical exercises exploring core DevOps tools and concepts, including containerization, orchestration, CI/CD, and infrastructure automation. Each exercise is organized as a standalone markdown file with step-by-step instructions, commands used, and supporting screenshots.

## Exercises

| # | Exercise | Description |
|---|---|---|
| 1 | [Kubernetes: Getting Started](1-Kubernetes-Getting-Started.md) | Deploying a containerized web app (Nginx) as a Pod on a local Kubernetes cluster using Minikube, and exposing it as a Service. |
| 2 | [Flask App Deployment](2-Flask-App-Deployment.md) | Building a custom Docker image and deploying a Flask app via a Kubernetes Deployment and Service on Minikube. |
| 3 | [Flashsale ReplicaSet Scaling](3-Flashsale-Replicaset-Scaling.md) | Scaling a Flask checkout service using a Kubernetes ReplicaSet, observing self-healing and pod distribution
| 4 | [Docker Networking: Multi-Container App](4-Docker-Networking-Multi-Container.md) | Building a custom Docker bridge network to connect a Flask API, MySQL, and Redis, and verifying inter-container communication. |
| 5 | [Docker Security with AppArmor](5-Docker-Security-AppArmor.md) | Investigating AppArmor-based container security, including a documented platform limitation on Docker Desktop for macOS. |
| 6 | [Monitoring with Prometheus & Grafana](6-Monitoring-Prometheus-Grafana.md) | Building a real-time metrics pipeline with Python, Prometheus, and Grafana, including a documented macOS Docker networking fix. |
| 7 | [CI & Jenkins Introduction](7-CI-Jenkins-Introduction.md) | Overview of Continuous Integration concepts and tools, plus installing and unlocking Jenkins via Docker. |

More exercises will be added here as the course progresses.

## Tools Used

- Kubernetes (Minikube)
- Docker
- kubectl
- Git & GitHub

