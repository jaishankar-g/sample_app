# sample_app
#Execute the commands below

kubectl apply -f mongo-secret.yaml

kubectl apply -f mongo.yaml

kubectl apply -f mongo-configmap.yaml 

kubectl apply -f mongo-express.yaml


kubectl get pod

kubectl get pod --watch

kubectl get pod -o wide

kubectl get service

kubectl get secret

kubectl get all | grep mongodb


kubectl describe pod mongodb-deployment-xxxxxx

kubectl describe service mongodb-service

kubectl logs mongo-express-xxxxxx

minikube service mongo-express-service
