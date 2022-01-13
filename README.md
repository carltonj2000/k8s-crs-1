# K8s Crash Course

The code in this repository is based on the
[Kubernetes Crash Course for Absolute Beginners](https://youtu.be/s_o8dwzRlu4)
video.

```bash
minikube start
echo -n mongouser | base64  # mongopassword
kubectl --help
kubectl get pod
kubectl get all
kubectl get configmap
kubectl get secret
kubectl apply -f mongo-config.yaml
kubectl apply -f mongo-secret.yaml
kubectl apply -f mongo.yaml
kubectl apply -f webapp.yaml
kubectl describe service webapp-service
kubectl logs <pod>
minikube ip # for ip of cluster
kubectl get node -o wide # ip to access webapp
```
