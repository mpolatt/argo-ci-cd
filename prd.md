I want to set up a local CI/CD pipeline using Kubernetes and ArgoCD. I already have a local Kubernetes cluster running on Kind. Here’s what I need:

1. Create a simple **Node.js Express API** (e.g., a counter API or a TODO API).
2. Write a `Dockerfile` to containerize the application.
3. Push the Docker image to a local or remote container registry (e.g., Docker Hub or a local registry).
4. Create Kubernetes manifests for deployment (`Deployment`, `Service`, `Ingress`).
5. Install and configure ArgoCD on my Kind cluster.
6. Create an **ArgoCD Application** manifest to manage deployments via GitOps.
7. Set up automatic updates in ArgoCD to deploy new versions from Git when changes are detected.
8. Configure a **CI/CD pipeline** (using GitHub Actions or Jenkins) to build, push, and deploy new versions automatically.

Make sure to use best practices for Kubernetes deployments, including proper resource requests/limits and health checks. The final goal is to have a fully automated CI/CD pipeline where each new commit triggers a deployment in my local Kubernetes cluster.
