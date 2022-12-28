# Kubernetes | K8s 101

![kubernetes-logo](https://upload.wikimedia.org/wikipedia/commons/thumb/3/39/Kubernetes_logo_without_workmark.svg/1200px-Kubernetes_logo_without_workmark.svg.png)

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

![differences](https://nickjanetakis.com/assets/blog/cards/docker-swarm-vs-kubernetes-which-one-should-you-learn-1fe9fd6549f5e0bbd2e0573d606db859322741aa29ad407e4dbae509da62dc44.jpg)

## Kubernetes VS Docker Swarm

1. **Advanced Features**: Kubernetes has a more comprehensive set of features for managing and orchestrating containers, including self-healing, rolling updates, and native support for stateful workloads.

2. **Custom Scheduler**: Kubernetes has a custom scheduler that allows you to specify how workloads should be placed on nodes based on resource constraints and other factors. This is not available in Docker Swarm.

3. **Ingress**: Kubernetes has a built-in ingress controller that allows you to easily expose services to the outside world. This is not available in Docker Swarm, which requires you to use an external ingress controller.

4. **Mature Ecosystem**: Kubernetes has a large and mature ecosystem, with a wide range of tools and resources available for managing and scaling containerized applications.

5. **Community**: Kubernetes has a larger and more established community, with a wider range of support and resources available. This can make it easier to find help and guidance when working with the platform.

| **Feature** | **Kubernetes** | **Docker Swarm** |
|:---:|:---:|:---:|
| Container Orchestration | Yes | Yes |
| Scaling | Yes | Yes |
| Load Balancing | Yes | Yes |
| Service Discovery | Yes | Yes |
| Self-Healing | Yes | Limited |
| Rolling Updates | Yes | Limited |
| Custom Scheduler | Yes | No |
| Ingress | Yes | Limited |
| Native Support for Stateful Workloads | Yes | Limited |
| Community | Large | Large |
| Maturity | Mature | Less mature |
| Complexity | High | Low |

* As you can see, both Kubernetes and Docker Swarm offer similar capabilities for container orchestration, scaling, load balancing, and service discovery.
* However, Kubernetes has more advanced features for self-healing, rolling updates, and native support for stateful workloads.
* It also has a custom scheduler and ingress capabilities, which are not available in Docker Swarm. Additionally, Kubernetes has a larger and more mature community, but it is also more complex to set up and use than Docker Swarm.


## Disadvantages of Kubernetes

1. **Complexity**: 
* Kubernetes can be complex to set up and manage, especially for large and complex deployments.
* It requires a significant amount of knowledge and expertise to effectively use and maintain a Kubernetes cluster.

2. **Resource Overhead**: 
* Kubernetes requires a certain amount of resources to run, including both CPU and memory.
* This can be an issue in environments where resources are constrained or where the overhead is not justified by the benefits of using Kubernetes.
  
3. **Compatibility Issues**: 
* Kubernetes is a rapidly evolving platform, and this can sometimes lead to compatibility issues with older versions or with certain tools and services.

4. **Lack of Flexibility**:
* Kubernetes has a certain set of features and capabilities that may not fit all use cases. 
* Some users may find that it is too rigid or inflexible for their needs.

5. **Cost**:
* Using Kubernetes can involve additional costs, such as the cost of running the cluster itself, as well as the cost of training and hiring personnel with the necessary expertise to manage it.

![disadvantages](https://media-exp1.licdn.com/dms/image/C4D12AQEb7GhYPA2_Mg/article-cover_image-shrink_720_1280/0/1520188856676?e=2147483647&v=beta&t=tljXxV5fU1UPenC172uEsmB8oWM2Wwvd2mJeAfcL99E)
