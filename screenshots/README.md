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
![image](https://user-images.githubusercontent.com/121487076/211201481-4282a174-737b-4ef5-a4f3-d2ccb39a5f45.png)


- To verify Kubernetes services are properly set up

```bash
kubectl describe services
```
![image](https://user-images.githubusercontent.com/121487076/211201185-87ce9e69-970e-4c22-a3ea-faa539536ad4.png)
![image](https://user-images.githubusercontent.com/121487076/211201210-7f1718e9-b11d-4cc9-af40-286abdefb216.png)


## Kubernetes Nodes

- Screenshot of your master and worker nodes

![image](https://user-images.githubusercontent.com/121487076/211201336-c57a9ec8-7391-47f6-b054-17f36ca3e664.png)
