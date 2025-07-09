Communicate to the cluster

You can interact with the cluster in two ways:

Imperative way
The imperative approach involves directly telling Kubernetes to perform an action through kubectl commands.

Declarative way
The declarative approach involves defining the desired state of your Kubernetes resources in configuration files (YAML or JSON, predominantly YAML) and then applying these files to the cluster.


Imperative way
To create a new pod
`kubectl run nginx-pod --image nginx:latest --port 80`

Get pod info

`kubectl get pods`

Describe the pod details

`kubectl describe pod nginx-pod`


![alt text](<Screenshot from 2025-07-09 10-39-39.png>)