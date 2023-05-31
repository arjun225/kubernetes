apiversion
kind
metadata : name of the pod, lables of pod, ip, expose service, ingress, connected to pod using lables
spection : container defination,  other defination



types of service
cluster ip : it only works on cluster leve

nodeport: we will expose our service using ip and port 
loadbalncer : it will create ip add for the deployment

external service
ingress : it will expose multiple appication with help of single ip add






resources
pod - lowlevel
deployment - high lowlevel  

lowlevel
pod=v1
services=v1
repicaset=v1

high level

deployment = apps/v1
ingrss= apps/v1
replication controller-v1


kubectl create or kubectl apply  to create resouces
kubectl edit to edit the resouces

kubectl describe about the reousces
kubectl delete  delete the resouces

