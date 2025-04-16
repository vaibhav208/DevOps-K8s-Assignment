# DevOps Kubernetes Assignment

## Task 1: Multinode Kubernetes Cluster

- 1 Master node: `master.bminfotrade.com`
- 2 Worker nodes: `worker1.com`, `worker2.com`
- Kubernetes setup using Vagrant and shell scripts
- Each worker node has a unique label
- Nodes can communicate with each other

## Task 2: Deploy CSS Template

- Custom Docker image: `<dockerhubusername>/bminfotrade:latest`
- CSS app exposed on port `3000`, mapped to hostPort `32000`
- Pod scheduling restricted to worker1 using `nodeSelector`

---

> Replace `<dockerhubusername>` with your actual Docker Hub username
