# check docker
'''sudo systemctl start docker
docker ps'''

# start kubernetes
'''minikube start'''

# check if any pods are running
kubectl get pods

using the yaml file
# start with 
    kubectl apply -f deployment.yaml

# check with 
    kubectl get pod
## get ip by adding the option
    kubectl get pod -o wide

# get really detailed info with 
    kubectl describe pod

# check the service
    minikube service nginx-service