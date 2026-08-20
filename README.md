# Kubernetes Local Cluster with Minikube

**Intern Name:** Rishabh Kumar Sinha  
**Intern ID:** CITS8600  
**Internship:** CODTECH DevOps Internship

## Project Description

This project demonstrates deploying a containerized Nginx web application on a local Kubernetes cluster using Minikube.

The Kubernetes deployment creates two Nginx Pods and a Service provides network access to the application.

## Technologies Used

- Kubernetes
- Minikube
- kubectl
- Nginx
- YAML
- GitHub Actions

## Project Structure

kubernetes-minikube/
├── deployment.yaml
├── service.yaml
├── README.md
└── .github/
    └── workflows/
        └── minikube.yml

## Kubernetes Architecture

User
  ↓
Kubernetes Service
  ↓
Nginx Pod 1
Nginx Pod 2

## Deployment

The `deployment.yaml` file creates an Nginx Deployment with two replicas.

The `service.yaml` file creates a NodePort Service that exposes the Nginx application.

## GitHub Actions Workflow

The workflow automatically:

1. Starts a Minikube cluster.
2. Checks the Kubernetes node.
3. Deploys the Nginx application.
4. Creates the Kubernetes Service.
5. Checks deployments and Pods.
6. Checks the Service.
7. Verifies the deployment rollout.

## Result

The Kubernetes Minikube CI workflow successfully started the cluster, deployed the Nginx application, created the Service, and verified the deployment.

## Learning Outcomes

This project demonstrates the fundamentals of Kubernetes, Minikube, Pods, Deployments, Services, kubectl commands, Kubernetes YAML configuration, and automated Kubernetes deployment using GitHub Actions.

**CODTECH Intern ID: CITS8600**
