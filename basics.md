# 🟢 Kubernetes Basics

## What is Kubernetes?
- Kubernetes (K8s) is an open-source container orchestration platform.
- Automates deployment, scaling, and management of containerized apps.

## Core Components
- **Pod**: Smallest unit, runs one or more containers.
- **Deployment**: Manages replicas of Pods.
- **Service**: Exposes Pods to the network.
- **ConfigMap / Secret**: Store configuration.
- **Node**: Worker machine in the cluster.

## Common Commands
```bash
kubectl get nodes
kubectl get pods -A
kubectl describe pod <pod-name>
kubectl logs <pod-name>



sadsadas