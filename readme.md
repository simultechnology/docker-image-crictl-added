# Docker image with crictl

## build
```bash
docker build -t docker-for-crictl:0.0.1 . --network=host
 ```

## add tag and push 
```bash
docker tag docker-for-crictl:0.0.1 127.0.0.1:5000/docker-for-crictl:0.0.1
docker push 127.0.0.1:5000/docker-for-crictl:0.0.1
```


```bash
kubectl apply -f sample-ds-dind.yaml
```
