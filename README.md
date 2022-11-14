# minikube crossplnae gke

# setup

crossplane setup: https://crossplane.io/docs/v1.10/getting-started/install-configure.html#choosing-your-crossplane-distribution

# start minikube

```bash
minikube start
```

# create gke

```bash
kubectl apply -f gke.yaml
```

# check status

```bash
kubectl get cluster
```

# remove gke

```bash
kubectl delete -f gke.yaml
```
