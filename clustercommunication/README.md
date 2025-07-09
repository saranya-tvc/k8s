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


Get the logs:
    Use the following

`kubectl logs nginx-pod`

To access the Nginx web page from our local browser for testing
Open a new terminal window and run

`kubectl port-forward pod/your-pod-name hostport:pod port`
            
(For eg: `kubectl port-forward pod/nginx-pod 8080:80` )

You need to run this in background : `kubectl port-forward pod/ngnx-pod 8080:80 & `

![alt text](<Screenshot from 2025-07-09 14-59-05.png>)


![alt text](<Screenshot from 2025-07-09 14-59-39.png>)


Delete Pod

`Kubectl delete pod podname`

`kubectl delete pod nginx-pod`

![alt text](<Screenshot from 2025-07-09 15-02-17.png>)