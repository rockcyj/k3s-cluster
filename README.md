# k3s-cluster
Launch a Kubernetes cluster with K3s and Docker compose

## Start a cluster
```
docker-compose up -d
```

## Stop a cluster
```
docker-compse down
```

## Kubernetes Cluster Config File
`.kubeconfig` file is generated under the current folder which can be used by `kubectl` command, eg: 
```
kubectl --kubeconfig=./kubeconfig.yaml get pod -A
```
