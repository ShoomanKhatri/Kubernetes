# Kubectl Cheatsheet


# Cluster Info
```sh
kubectl cluster-info
```
```sh
kubectl config view
```
```sh
kubectl get nodes
```


# Working with Contexts

```sh
kubectl config get-contexts
```
```sh
kubectl config current-context
```
```sh
kubectl config use-context <context-name>
```

# Get Resources

```sh
kubectl get all
```
```sh
kubectl get pods
```
```sh
kubectl get services
```
```sh
kubectl get deployments
```
```sh
kubectl get nodes
```
```sh
kubectl get namespaces
```


# Describe Resources

```sh
kubectl describe pod <pod-name>
```
```sh
kubectl describe service <service-name>
```
```sh
kubectl describe deployment <deployment-name>
```

# Creating and Deleting Resources

```sh
kubectl create -f <file.yaml>
```
```sh
kubectl delete -f <file.yaml>
```
```sh
kubectl delete pod <pod-name>
```
```sh
kubectl delete service <service-name>
```
```sh
kubectl delete deployment <deployment-name>
```
# Get Logs
```sh
kubectl logs <pod-name>
```
```sh
kubectl logs <pod-name> -c <container-name>
```
