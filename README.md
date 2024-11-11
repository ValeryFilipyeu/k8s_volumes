# k8s_volumes

all cli:

docker build -t valeryfilipyeu/kub-story:2 .
docker push valeryfilipyeu/kub-story:2 
kubectl apply -f=deployment.yaml and any other config file
kubectl get configmap
minikube service story-service
kubectl get deployments 
minikube status
kubectl delete -f=deployment.yaml
kubectl get services
