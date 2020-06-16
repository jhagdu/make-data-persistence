# make-data-persistence
This contains the YAML configuration files of K8s resources to make Prometheus and Grafana Pod data Persistence 

Pre-requisite :-  
minikube and kubectl should be installed and configured configured

Clone or Download this and then run by :-  
kubectl apply -k .  
  
This will create deployment, pods, PVC, service for us. And this will also make our Prometheus and Grafana data Persistence  
