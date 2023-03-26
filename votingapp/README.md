# Voting app

Example microservice app that is going to be deployed using Kind locally. 

1. First we are going to have to have Docker running: 
2. Second have Kind installed. 
3. Third spin up a kind cluster and give it a name. 

To apply and test test: 
- Create: `kubectl create -f voting-app-pod.yaml`
- Creating the service: `kubectl create -f voting-app-service.yaml`

Checking the status of the pod and service: 
- `kubectl get pods,svc` this will list both pods and service. 

If you're using minikube. you can use the `url` flag for the service to see the url and the port. 
- `minikube service voting-service --url` 


### TODO: run this with minikube as well. 


## Creating a deployment: 
- This will create a replicaset and you manage easier. 

