```
pip install -r requirements.txt
```

```
istioctl kube-inject -f helloworld.yaml -o helloworld-istio.yaml
```

## START
```
kubectl create -f helloworld-istio.yaml
kubectl create -f helloworld-gateway.yaml
```