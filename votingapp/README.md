# Voting app
Example microservice app used for practice.

## Setup: 
1. Install [Docker Desktop](https://www.docker.com/products/docker-desktop/)
2. Install [minikube](https://minikube.sigs.k8s.io/docs/start/)

### miniKube
I installed it using brew. `brew install minikube`. 
At the time of this, I installed this following version: `version: v1.29.0`

```
brew install minikube

which minikube

minikube version
```

## Running this example app: 

To apply and test test: 
- Create: `kubectl create -f [path/to/voting-app-pod.yaml]`
- Creating the service: `kubectl create -f [path/to/voting-app-service.yaml]`

Checking the status of the pod and service: 
- `kubectl get pods,svc` this will list both pods and service. 

If you're using minikube. you can use the `url` flag for the service to see the url and the port. 
- `minikube service voting-service --url` 




## Resources: 
- Udemy: "Kubernetes for absolute beginners - Hands on" by Mumshad Mannambeth
- [minikube](https://minikube.sigs.k8s.io/docs/start/)
- Optional [kind](https://kind.sigs.k8s.io/docs/user/quick-start/) at the time of `kind v0.14.0 go1.18.2 darwin/arm64`.
- [kodeckoudhub/example-voting-app-kubernetes](https://github.com/kodekloudhub/example-voting-app-kubernetes)
- [dockersamples/example-voting-app](https://github.com/dockersamples/example-voting-app) 




