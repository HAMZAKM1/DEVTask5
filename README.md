# Task 5: Build a Kubernetes Cluster with Minikube

## Objective
Deploy and manage applications in Kubernetes using Minikube.

## Tools Used
- Minikube
- kubectl
- Docker

## Steps Performed
1. Installed Minikube and started cluster.
2. Created nginx deployment using deployment.yaml.
3. Exposed application using service.yaml.
4. Verified pods using:
   kubectl get pods
5. Scaled deployment:
   kubectl scale deployment nginx-deployment --replicas=4
6. Used describe and logs for inspection.

## Screenshots
## 📸 Screenshots

### Cluster Status
![Nodes](screenshots/get-nodes.png)

### Running Pods
![Pods](screenshots/get-pods.png)

### Service Details
![Service](screenshots/get-svc.png)

### Scaled Deployment (4 Replicas)
![Scaled Pods](screenshots/scaled-pods.png)

### Nginx Output in Browser
![Nginx](screenshots/nginx-browser.png)   this my  README.md   but not showing  github 

![Nginx](screenshots/nginx-browser.png)

