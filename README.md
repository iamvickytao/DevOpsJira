Deploy 

cd jira path 

kubectl create ns jira 

kubectl create -f jira-deployment-service.yaml 

kubectl create -f jira-deployment.yaml 
kubectl delete ns jira 
