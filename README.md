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
More exercises will be added here as the course progresses.

## Tools Used

- Kubernetes (Minikube)
- Docker
- kubectl
- Git & GitHub

## Repository Structure

Hamzah-DevOps-Lab/
├── README.md
├── 1-Kubernetes-Getting-Started.md
├── 2-Flask-App-Deployment.md
├── 3-Flashsale-Replicaset-Scaling.md
├── flask-k8s-exercise/
│   ├── app.py
│   ├── Dockerfile
│   └── flask-deployment.yaml
├── flashsale-k8s-exercise/
│   ├── app.py
│   ├── Dockerfile
│   └── flashsale-replicaset.yaml
└── Images/
    ├── cluster-ready.png
    ├── pod-running.png
    ├── nginx-welcome-page.png
    ├── flask-minikube-status.png
    ├── flask-docker-build.png
    ├── flask-kubectl-apply.png
    ├── flask-deployment-status.png
    ├── flask-curl-response.png
    ├── flashsale-minikube-status.png
    ├── flashsale-docker-build.png
    ├── flashsale-apply.png
    ├── flashsale-initial-pods.png
    └── flashsale-self-heal.png

