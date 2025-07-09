# k8s
Self studying Portal


Creating a cluster using Kind

`kind create cluster`
![alt text](<Screenshot from 2025-07-09 08-39-36.png>)

install kubectl

verify the cluster

`kubectl get nodes`

to get more detail aboyt node use the command

`kubectl get nodes -o wide`
![alt text](<Screenshot from 2025-07-09 10-17-37.png>)


To get more detail about the cluster

`kubectl cluster-info dump`

![alt text](<Screenshot from 2025-07-09 10-19-50.png>)

List the cluster

`kind get clusters`

![alt text](<Screenshot from 2025-07-09 10-21-49.png>)
