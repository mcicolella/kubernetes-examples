# cert-manager

## Create new namespace

$ kubectl create namespace cert-manager

## Static installation

$ kubectl apply -f https://github.com/jetstack/cert-manager/releases/download/v1.6.1/cert-manager.yaml

## Check for running pods

$ kubectl get pods --namespace cert-manager

