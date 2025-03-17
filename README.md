# OCP
OCP Installation 


## Kubernetes & OpenShift Components
===========================================================================================================================================================================
**KUBE_API**: It manages authentication + authorization, it has by default multiple resources.  
**OpenShift_API**: New API created, it has different types of resources available, created by API aggregation.  
**ETCD**: It is a persistent key-value database for Kubernetes.  
**OpenShift-OAuth**: Handles user authentication and security policies.  
**OpenShift-Controller**: OpenShift-specific controllers like Route and SCC (Security Context Constraints).  
**STATIC PODS**: [KUBE_API | SCHEDULER | ETCD | CONTROLLER] are static pods managed by Kubelet.  
  - Location: `/etc/kubernetes/manifests`  
**CONTROL PLANE**: Services are containerized instead of modifying the OS, called Control Plane Node.  
**CRI-O**: Container runtime interface socket for Kubernetes.  
**Container Runtime**: Dockerd, containerd - provides an environment to create containers.  
**PODMAN, DOCKER, CRICTL**: Utilities to interact with the container runtime daemon.  
**Container Socket**: Communication interface for container management.  
==============================================================================================================================================================================

**Container socket=commincation interface.**
**dockerd=/var/run/docker.sock.**
**containerd=/run/containerd/containerd.sock.**
**cri-o =/var/run/cri.sock.**
==============================================================================================================================================================================
**OPENSHIFT INSTALLATION IN BAREMETAL**




![Image Alt](https://github.com/ubuntomathur/OCP/blob/main/2025-03-17_18-59-42.png)


