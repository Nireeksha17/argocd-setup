# argocd-setup

https://argo-cd.readthedocs.io/en/stable/

#install Argo CD in kubernetes
kubectl create namespace argocd
kubectl apply -n argocd -f https://raw.githubusercontent.com/argoproj/argo-cd/stable/manifests/install.yaml
