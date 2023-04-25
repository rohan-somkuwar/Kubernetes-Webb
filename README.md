# Kubernetes-Webb App
![Screenshot from 2023-04-25 12-19-31](https://user-images.githubusercontent.com/100048559/234285495-7925fa63-da51-4020-8fcb-38d18590bfb3.png)

# Kubernetes Architecture and Components, Kubernetes Installation and Configuration


# Kubernetes
Kubernetes is an open-source container orchestration platform that automates the deployment, scaling and management of the containerized application. Its main feature is automatic container placement self-healing and scalability.

Kubernetes is a tool that helps developers deploy, manage and scale their applications in an automated way. It allows developers to package their applications into containers and deploy them to cluster machines. Kubernetes take care of managing and scaling them as needed.

# Kubernetes Architecture
![Docekr-Architecture](https://user-images.githubusercontent.com/100048559/234293589-b218ccfe-86a9-44b6-b973-fecb43329c96.jpeg)

# Kubernetes Components
# Master Node
# Kube API Server
The kube API server is a component to communicate with the control panel, kube scheduler, etc, kube controller manager

# Kube Scheduler
It is responsible for assigning pods to needs in the cluster based on resource availability and other constraints. (when a new pod is created, the schedular receives the pod specification and selects a suitable node for pods to run on.)

# Etcd
Kubernetes components store and configure data state information and metadata about the cluster.

# Kube Controller Manager
It is responsible for monitoring the state of various resources within the cluster and taking corrective actions as needed to bring the cluster to the desired state.

# Worker Node

# Kubelet
The components run on each worker node in the Kubernetes cluster and are responsible for managing the containers running on that nodes.

# Kube-proxy
It is responsible for handling network traffic in the Kubernetes cluster. It setups network routing rules and load balancing for the containers running on each node.

# Pod
Pods are the Smallest unit of Kubernetes that represent one or more containers.

* Kubernetes Installation and Configuration
Kubeadm and Minikube are both tools that facilitate the deployment and management of Kubernetes Clusters but they are different purposes.

