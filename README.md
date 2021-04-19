# kubernetes

```
kubectl delete pods <pod> -n redis --grace-period=0 --force
kubectl patch pod <pod> -p '{"metadata":{"finalizers":null}}'
```


Ingress Example
https://github.com/nginxinc/kubernetes-ingress/tree/master/examples/complete-example
https://www.digitalocean.com/community/tutorials/how-to-set-up-an-nginx-ingress-on-digitalocean-kubernetes-using-helm

Cluster upgrade
https://kubernetes.io/docs/tasks/administer-cluster/kubeadm/kubeadm-upgrade/

Kubernetes Intro
https://www.digitalocean.com/community/tutorials/an-introduction-to-kubernetes

Kubernetes Tutorial
https://www.digitalocean.com/community/meetup_kits/getting-started-with-containers-and-kubernetes-a-digitalocean-workshop-kit

