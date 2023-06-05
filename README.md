# QA Pods

```sh
kubectl create ns qa
kubectl apply -n qa -f https://raw.githubusercontent.com/jessegoodier/qa-pods/main/cpu-limit-eq-request.yaml
kubectl apply -n qa -f https://raw.githubusercontent.com/jessegoodier/qa-pods/main/cpu-limit-no-request.yaml
kubectl apply -n qa -f https://raw.githubusercontent.com/jessegoodier/qa-pods/main/memory-limit-eq-request.yaml
kubectl apply -n qa -f https://raw.githubusercontent.com/jessegoodier/qa-pods/main/memory-limit-no-request.yaml
kubectl apply -n qa -f https://raw.githubusercontent.com/jessegoodier/qa-pods/main/no-load-with-requests.yaml
kubectl apply -n qa -f https://raw.githubusercontent.com/jessegoodier/qa-pods/main/init-container-pod.yaml
```
