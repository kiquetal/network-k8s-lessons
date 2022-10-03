### Course: Advanced-networking-with-for-k8s-aws


### Cluster Networking

- Host Routing
- Cluster Ip
- Private IPs (pod)

![network-connectivity](./imagez/network-connectivity.png)


### Overlay Network



> Route tables only allows 50 rules

![aws-vpc-cni](./imagez/aws-vpc-cni.png)

![network-component.png](./imagez/network-component.png)


### Cluster DNS

- Run as deployment with replica of 2.
pod
  spc.dnsPolicy: default | ClusterFirst | ClusterFirstWithHostNet | None

![kube-dns](./imagez/kube-dns.png)
