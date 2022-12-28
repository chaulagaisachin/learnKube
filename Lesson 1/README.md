# Kubernetes | K8s 101

## Introduction
Kubernetes is a complex and constantly-evolving platform that makes it easy to deploy and manage containerized applications at scale (said no one ever).

Kubernetes is a revolutionary technology that makes it easy to deploy and manage containerized applications at scale. 
Just kidding, it's actually a massive, complex, and constantly-evolving platform that requires a lot of time and effort to understand and use effectively. 
But hey, at least it's open source and widely adopted, so you can't really go wrong by learning it, right?

* In all seriousness, Kubernetes is a container orchestration platform that was developed by Google and is now maintained by the Cloud Native Computing Foundation. 
* It is designed to manage the deployment, scaling, and maintenance of containerized applications in a cluster of machines. 
* It provides a wide range of features and functionality, including automatic scheduling and placement of containers, self-healing capabilities, and support for rolling updates and rollbacks.

Despite its complexity, Kubernetes has become the de facto standard for container orchestration, and is used by many organizations to manage their containerized applications in production environments.
It is a powerful and flexible platform that can be used to manage a wide range of workloads, from simple web applications to complex distributed systems.


## Kubernetes VS Docker Swarm

1. **Advanced features**: Kubernetes has a more comprehensive set of features for managing and orchestrating containers, including self-healing, rolling updates, and native support for stateful workloads.

2. **Custom scheduler**: Kubernetes has a custom scheduler that allows you to specify how workloads should be placed on nodes based on resource constraints and other factors. This is not available in Docker Swarm.

3. **Ingress**: Kubernetes has a built-in ingress controller that allows you to easily expose services to the outside world. This is not available in Docker Swarm, which requires you to use an external ingress controller.

4. **Mature ecosystem**: Kubernetes has a large and mature ecosystem, with a wide range of tools and resources available for managing and scaling containerized applications.

5. **Community**: Kubernetes has a larger and more established community, with a wider range of support and resources available. This can make it easier to find help and guidance when working with the platform.

| **Feature** | **Kubernetes** | **Docker Swarm** |
|:---:|:---:|:---:|
| Container orchestration | Yes | Yes |
| Scaling | Yes | Yes |
| Load balancing | Yes | Yes |
| Service discovery | Yes | Yes |
| Self-healing | Yes | Limited |
| Rolling updates | Yes | Limited |
| Custom scheduler | Yes | No |
| Ingress | Yes | Limited |
| Native support for stateful workloads | Yes | Limited |
| Community | Large | Large |
| Maturity | Mature | Less mature |
| Complexity | High | Low |
