# K8s Architecture

![architecture](https://phoenixnap.com/kb/wp-content/uploads/2021/04/full-kubernetes-model-architecture.png)

1. **Master node**: 
* The master node is the central control plane for the Kubernetes cluster. 
* It is responsible for maintaining the desired state of the cluster, scheduling workloads, and providing the API server for interacting with the cluster.

2. **Worker nodes**: 
* Worker nodes are the nodes that actually run the containerized applications. 
* They are managed by the master node and receive instructions on which containers to run and how to run them.

3. **Etcd**: 
* Etcd is a distributed key-value store that is used by the Kubernetes master to store the cluster's desired state.
* Open source distributed key-value store used to hold and manage the critical information that distributed systems need to keep running. Most notably, it manages the configuration data, state data, and metadata for Kubernetes

4. **API server**: 
* The API server is the interface through which users and clients can interact with the cluster. 
* It exposes a RESTful API that can be used to create, read, update, and delete resources in the cluster.

5. **Controller manager**: 
* The controller manager is responsible for monitoring the desired state of the cluster and making changes to the actual state to ensure that it matches the desired state.

6. **Scheduler**: 
* The scheduler is responsible for placing workloads onto worker nodes based on the available resources and the constraints specified in the workload's configuration.

7. **Kubelet**: 
* The kubelet is the agent that runs on each worker node and is responsible for starting and stopping containers as directed by the master node.

8. **Pod**: 
* A pod is the basic unit of deployment in Kubernetes. It is a logical host for one or more containers that are related to each other and should be deployed together.

![compare](https://i.stack.imgur.com/s0TJ1.png)

## Kubernetes Architecture vs Docker Swarm Architecture

| Components | **Kubernetes** | **Docker Swarm** |
|:---:|:---:|:---:|
| Master Node | Central control plane that maintains desired state of cluster and schedules workloads | No central control plane; all nodes are equal and can be used to run workloads |
| Worker Nodes | Managed by master node and receive instructions on which containers to run | Managed using a leader election process |
| API Server | Exposes a RESTful API for interacting with the cluster | Exposes an API for interacting with the cluster |
| Scheduler | Responsible for placing workloads onto worker nodes based on available resources and constraints | Responsible for placing workloads onto worker nodes based on available resources and constraints |