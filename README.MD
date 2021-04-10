## Description

[K8S](https://kubernetes.io/) Production-Grade Container Orchestration.

## Create Deployment 

```bash
$ kubectl apply -f k8s/client-deployment.yaml
```

## Create Deployment Shortcuts

```bash
$ kubectl apply -f k8s
```

## Get Deployments

```bash
$ kubectl get deployment
```

## Get Pods

```bash
$ kubectl get pods
```

## Get Services

```bash
$ kubectl get services
```

## Get Logs

```bash
$ kubectl logs <pods_name>
```

## Get Storage

```bash
$ kubectl get storageclass
$ kubectl describe storageclass
```

## Get Persistent Volume

```bash
$ kubectl get pv
$ kubectl get pvc
```

## Delete Deployment 

```bash
$ kubectl delete deployment client-deployment
```

## Delete Service

```bash
$ kubectl delete service client-node-port
``````

## Creating a Secret 
![1](https://user-images.githubusercontent.com/56122568/113734450-06856180-9704-11eb-9321-5e3cc238422a.png)


