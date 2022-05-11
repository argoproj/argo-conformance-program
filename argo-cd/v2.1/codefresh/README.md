# Guide of how to run e2e

1. create a new k8s cluster (can be any dsitribution)
2. install codefresh argo cd distribution on a k8s cluster

```
kubectl create namespace argocd
kubectl apply -n argocd -f https://raw.githubusercontent.com/codefresh-io/argo-cd/release-2.1/manifests/install.yaml
```

3. follow the official guide of argo cd for e2e execution: https://argo-cd.readthedocs.io/en/stable/developer-guide/test-e2e/

E2E has been run automatically inside the repository [codefresh-io/argo-cd](https://github.com/codefresh-io/argo-cd/runs/4691172364?check_suite_focus=true)
