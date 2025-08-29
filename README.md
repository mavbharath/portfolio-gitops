# portfolio-gitops

Imp Commands used 

helm install web-app ./helm-test -n app --create-namespace

kubectl get pods -n app
kubectl get svc -n app

argocd app list
argocd app get flask-app

Force sync:
argocd app sync flask-app
