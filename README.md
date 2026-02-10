# migration-ingress_gapi
migration ingress vers gateway Api 


mise en place du scenario

kubectl apply -f https://raw.githubusercontent.com/kubernetes/ingress-nginx/controller-v1.9.1/deploy/static/provider/cloud/deploy.yaml

verification des ressources 
kubectl get pods -n ingress-nginx


