# My Next.js Dockerized App

This is a simple **Next.js** application containerized with **Docker**, deployed on **Kubernetes (Minikube)**, and automated via **GitHub Actions**.

---

## Project Structure

my-next-app/
├─ app/ # Next.js app code
├─ public/ # Static assets
├─ k8s/ # Kubernetes manifests
│ ├─ Deployment.yaml
│ └─ service.yaml
├─ Dockerfile
├─ .github/workflows/ # GitHub Actions workflow
└─ README.md



---

## Prerequisites

- Node.js >= 20
- npm
- Docker
- Minikube
- kubectl
- Git

---

## Setup Locally

1. Clone the repository:

```bash
git clone https://github.com/<your-username>/my-new-app.git
cd my-new-app

