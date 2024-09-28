

Create the secret for elasticsearch , see the secret.yaml 
```
kubectl apply -f secret.yaml -n logging 
```

Reference: https://github.com/elastic/helm-charts/blob/main/elasticsearch/README.md

helm upgrade --install elasticsearch elastic/elasticsearch -f values.yaml  -n logging --version 8.5.1

