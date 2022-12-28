# Kubernetes Introduction
Kubernetes is a complex and constantly-evolving platform that makes it easy to deploy and manage containerized applications at scale (said no one ever).

Kubernetes is a revolutionary technology that makes it easy to deploy and manage containerized applications at scale. 
* Just kidding, it's actually a massive, complex, and constantly-evolving platform that requires a lot of time and effort to understand and use effectively. 
* But hey, at least it's open source and widely adopted, so you can't really go wrong by learning it, right?

* In all seriousness, Kubernetes is a container orchestration platform that was developed by Google and is now maintained by the Cloud Native Computing Foundation. 
* It is designed to manage the deployment, scaling, and maintenance of containerized applications in a cluster of machines. 
* It provides a wide range of features and functionality, including automatic scheduling and placement of containers, self-healing capabilities, and support for rolling updates and rollbacks.

Despite its complexity, Kubernetes has become the de facto standard for container orchestration, and is used by many organizations to manage their containerized applications in production environments.
It is a powerful and flexible platform that can be used to manage a wide range of workloads, from simple web applications to complex distributed systems.


![architecture](https://phoenixnap.com/kb/wp-content/uploads/2021/04/full-kubernetes-model-architecture.png)

**Master node**: 
* The master node is the central control plane for the Kubernetes cluster. 
* It is responsible for maintaining the desired state of the cluster, scheduling workloads, and providing the API server for interacting with the cluster.

**Worker nodes**: 
* Worker nodes are the nodes that actually run the containerized applications. 
* They are managed by the master node and receive instructions on which containers to run and how to run them.

**Etcd**: 
* Etcd is a distributed key-value store that is used by the Kubernetes master to store the cluster's desired state.

**API server**: 
* The API server is the interface through which users and clients can interact with the cluster. 
* It exposes a RESTful API that can be used to create, read, update, and delete resources in the cluster.

**Controller manager**: 
* The controller manager is responsible for monitoring the desired state of the cluster and making changes to the actual state to ensure that it matches the desired state.

**Scheduler**: 
* The scheduler is responsible for placing workloads onto worker nodes based on the available resources and the constraints specified in the workload's configuration.

**Kubelet**: 
* The kubelet is the agent that runs on each worker node and is responsible for starting and stopping containers as directed by the master node.

**Pod**: 
* A pod is the basic unit of deployment in Kubernetes. It is a logical host for one or more containers that are related to each other and should be deployed together.

![compare](https://i.stack.imgur.com/s0TJ1.png)