# cert-manager

## Create new namespace

$ kubectl create namespace cert-manager

## Static installation

$ kubectl apply -f https://github.com/jetstack/cert-manager/releases/download/v1.6.1/cert-manager.yaml

## Check for running pods

$ kubectl get pods --namespace cert-manager

## Issue a self signed certificate 

$ kubectl apply -f test-cert-manager.yaml

$ kubectl describe certificate -n cert-manager-test


