# OCP
OCP Installation 


KUBE_API: it manages authentication + authorization, it has by default multiple resources
openshift_API: new api created it has different types of resources available, it has created by api aggeration 
ETCD= it is persistent stored database in the form key value
openshift-oath- it handles the user authentication and security polices 
openshift-controller -it is openshift based specific controller like as route and scc[security context contraints]
STATIC PODS- [KUBE_API|SCHEDULAR|ETCD| CONTROLLER] are static pods, those pods are created by one daemon service that is kubelet 
its location is /etc/kubernetes/manifest
CONTROL PLANE - we are not changing the operating system and services are going into containered format that we call it Control Plane Node]
CRI-O-container socket 
Container runtime - Dockerd, containered , runtime means with the help of this , it provides the enviroment to create the container 
PODMAN, DOCKER,CRICTL - utility that is used to talk to your daemon,

Container socket =commincation interface
dockerd=/var/run/docker.sock
containerd=/run/containerd/containerd.sock
cri-o =/var/run/cri.sock



![Image Alt](https://github.com/ubuntomathur/OCP/blob/main/2025-03-17_18-59-42.png)


