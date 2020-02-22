# k8s-labs
Getting started with k8s environmnet using apps from a [Golang Sample Repository](https://github.com/tiagotele/golangsample).

## Deploy on your own cluster:

```bash
$ cd first-app
$ kubectl -n <NAMESPACE> create -f first-app-pod.yml -f first-app-service.yml
```

### If you are using [Minikube](https://github.com/kubernetes/minikube) you can access from your browser using:
```bash
$ cd first-app
$ minikube -n <NAMESPACE> service golang-sample-service --url
```
