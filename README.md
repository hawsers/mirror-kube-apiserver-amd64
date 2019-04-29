# sh commands

```sh

VERSION=${VERSION}

docker pull hawsers/kube-apiserver-amd64:${VERSION}
docker tag hawsers/kube-apiserver-amd64:${VERSION} k8s.gcr.io/kube-apiserver-amd64:${VERSION}
docker rmi hawsers/kube-apiserver-amd64:${VERSION}
```
