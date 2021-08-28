# ArgoCD
#### Instalacion 
helm install argo-cd argo/argo-cd -n argocd
kubectl port-forward svc/argo-roldyx-argocd-server -n argocd 8080:443

argocd app list 

argocd app sync helm-hooks
