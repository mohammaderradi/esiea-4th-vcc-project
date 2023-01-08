# Screenshots

To help review your deployment, please include the following screenshots in this directory::

## Deployment Pipeline

- DockerHub showing containers that you have pushed

![image](https://user-images.githubusercontent.com/121487076/211200435-b85f0ca7-024c-438d-8d08-260de228b568.png)

- Docker containers created by docker compose up -d command (docker ps)

![image](https://user-images.githubusercontent.com/121487076/211200803-5cf2b532-91f7-4b32-81c4-1e63b69747b7.png)


## Kubernetes

- To verify Kubernetes pods are deployed properly

```bash
kubectl get pods
```

- To verify Kubernetes services are properly set up

```bash
kubectl describe services
```

- To verify that you have set up logging with a backend application

```bash
kubectl logs {pod_name}
```

## Kubernetes Nodes

- Screenshot of your master and worker nodes
