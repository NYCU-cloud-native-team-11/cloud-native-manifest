# Cloud Native Manifest

## Requirement

- Helm v3
- K8s cluster

## Install

1. Change image name, image tag and url in values.yaml

2. Check K8s cluster is vaild

```
kubectl get nodes
```

3. Check helm version

```
helm version
```

4. install helm application

```
helm install cloud-native-project .
```

5. check the installation is complete

```
helm list
```