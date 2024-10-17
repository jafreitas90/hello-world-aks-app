# Deploying a Kubernetes Application with Infrastructure as Code (IaC)

Deploying a Kubernetes Application with Infrastructure as Code (IaC)
This repository contains a basic example of how to deploy a Kubernetes application using Infrastructure as Code (IaC) with Minikube for local development and Azure Kubernetes Service (AKS) for production. The application is based on the agnhost:2.39 image from the public Kubernetes image registry, and it uses Kubernetes YAML manifests to define the deployment, service, and (optionally) ingress.

Project Structure

```c#
hello-world-aks-app/
├── deploy/
│ ├── deployment.yaml # Kubernetes Deployment manifest
│ ├── service.yaml # Kubernetes Service manifest
│ └── ingress.yaml # Kubernetes Ingress manifest (optional)
└── README.md # Project documentation (this file)
```

## Kubernetes Manifests

`deployment.yaml`: Defines the application deployment, including replica count, container image, and ports.
`service.yaml`: Exposes the application using a Kubernetes Service. By default, it uses NodePort for local development.
`ingress.yaml (optional)`: Sets up an Ingress for external access via a domain name (useful for production environments).

More details <a href="https://readme.com/" target="_blank">here</a>
