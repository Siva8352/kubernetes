# kubernetes

This is a simple setup to deploy the Mongo database and Mongo Express App.

#### Prerequisites
- Docker
- Minikube

---

1. Clone the repository to your local environment and navigate to the kubernetes folder.
2. Ensure the files, i.e., secrets.yaml, mongo-config.yaml, mongo-app.yaml, web-app.yaml
3. Start the Minikube cluster
4. Create the secret using the below command
```
kubectl apply -f secrets.yaml
```
5. Similarily the above step creating the secret, run all the files similarily with kubectl.
6. Ensure the Pods running
7. Access the Minikube services to access the express app which connects the Mongo database
```
minikube service --all
```
8. Access the webapp-deployment URL and access the Mongo DB

Hurray!!!!, we have deployed a MERN APP with kubernetes.
