# K8S-For-DevOps
### 
1- Install k8s cluster (minikube)
2- Create a pod with the name redis and with the image redis.
<img width="959" height="326" alt="image" src="https://github.com/user-attachments/assets/029abeb5-ebcd-4333-b9ea-010bc67a0c11" />


3- Create a pod with the name nginx and with the image “nginx123”

<img width="959" height="326" alt="image" src="https://github.com/user-attachments/assets/b55e8bac-86e1-41b0-8f10-c6a9b09178f5" />

Use a pod-definition YAML file.
4- What is the nginx pod status?
5- Change the nginx pod image to “nginx” check the status again
6- How many ReplicaSets exist on the system?
7- create a ReplicaSet with
name= replica-set-1
image= busybox
replicas= 3
8- Scale the ReplicaSet replica-set-1 to 5 PODs.
9- How many PODs are READY in the replica-set-1?
10- Delete any one of the 5 PODs then check How many PODs exist now?
Why are there still 5 PODs, even after you deleted one?
11- How many Deployments and ReplicaSets exist on the system?
12- create a Deployment with
name= deployment-1
image= busybox
replicas= 3
13- How many Deployments and ReplicaSets exist on the system now?
14- How many pods are ready with the deployment-1?
15- Update deployment-1 image to nginx then check the ready pods again
16- Run kubectl describe deployment deployment-1 and check events
What is the deployment strategy used to upgrade the deployment-1?
17- Rollback the deployment-1
What is the used image with the deployment-1?
18- Create a deployment using nginx image with latest tag only and remember to
mention tag i.e nginx:latest and name it as nginx-deployment. App labels should be
app: nginx-app and type: front-end. The container should be named as
nginx-container; also make sure replica counts are 3.
