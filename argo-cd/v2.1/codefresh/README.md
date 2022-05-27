# Guide of how to run e2e

1. Create a new K8s cluster (can be any distribution)
2. Install Codefresh Argo CD Distribution

```
kubectl create namespace argocd-e2e
kubectl apply -n argocd -f https://raw.githubusercontent.com/codefresh-io/argo-cd/release-2.1/manifests/install.yaml
```

3. Follow the official guide of Argo CD for e2e execution: https://argo-cd.readthedocs.io/en/stable/developer-guide/test-e2e/
