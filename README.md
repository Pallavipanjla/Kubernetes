# Kubernetes
# Steps:
**1.Install Minikube and start the Kubernetes cluster:**
-> minikube start

**2. Create deployment.yaml**

**3. Apply the deployment**
-> kubectl apply -f deployment.yaml

**4. Create service.yaml to expose the deployment**

**5. Apply the service:**
-> kubectl apply -f service.yaml

**6. Verify the deployment:**
-> kubectl get pods
-> kubectl get services

**7. Scale the deployment:**
-> kubectl scale deployment nginx-deployment --replicas=4

**8. View pod details:**
-> kubectl describe pod <your-pod-name>

**9. Get logs for a pod:**
-> kubectl logs <your-pod-name>

**10. Access the application in the browser:**
-> minikube service nginx-service
