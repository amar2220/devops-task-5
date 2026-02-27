 Kubernetes Deployment using Minikube (Task 5)
 
 Objective

Deploy and manage a containerized application using Kubernetes locally with Minikube.

 Tools Used

* Docker Desktop
* Minikube
* kubectl
* VS Code

 📂 Project Files

* deployment.yaml
* service.yaml

##  Steps Performed

### 1️⃣ Start Minikube

minikube start --driver=docker

### 2️⃣ Deploy application

kubectl apply -f deployment.yaml

### 3️⃣ Expose service

kubectl apply -f service.yaml

### 4️⃣ Check pods

kubectl get pods

### 5️⃣ Check services

kubectl get services

### 6️⃣ Access application

minikube service myapp-service


## 📸 Output

* Pods running successfully
* Service exposed using NodePort
* Application opened in browser (Nginx Welcome Page)

---

## ✅ Result

Successfully deployed and exposed an application using Kube
