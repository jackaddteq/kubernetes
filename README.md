# kubernetes

```
apt install -y iproute2  # ip 
apt install dnsutils  # nslookup
apt install net-tools  # netstat
apt-get install iputils-ping  # ping



tmux
ctr-b %  # add vertical pane
ctr-b <-  -> # switch pane ctr-b arrow
ctr-b "  # add horizontal pane

ctr-b c  # add window
ctr-b 1  # switch to 1
ctr-b ,  # rename window
```

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

