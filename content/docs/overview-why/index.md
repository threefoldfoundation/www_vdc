---
description: ''
sidebar: 'docs'
prev: '/docs/'
next: '/docs/overview-secure/'
---

# Why use TF VDC?

## Benefit from Agility of Cloud

TF VDC allows you to create a Virtual Data Center out of the box, with tooling that is widespread in the developers' community. Containers and the orchestration of it through Kubernetes offers the following benefits: 

Containers: 
- Provide a very agile application creation and deployment, with an easy and efficient creation of the container image compared to VMs
- Allow for a continuous development, integration and deployment, with quick and easy rollback
- Applications are decoupled from infrastructure, hereby isolating the development and operations concerns from each other
- Easy management of signals on application health and behaviour
- Execution of an application happens in the same way on a laptop as in the cloud
- Enables a full abstraction between running an OS and running an application within this OS
- Allows for a microservices architecture, cutting applications into small, independent building blocks, which can interact in a dynamic way
- It encapsulates the application in a way that behaviour at runtime becomes predictable
- An efficient use of hardware resources is possible

Orchestration through Kubernetes provides you with extra services without effort: 
- Easy set up and manage the execution of containers and the interaction between containers
- Services to facilitate access using DNS or using IP address
- Automated load balancing in case of high traffic
- Automated rollbacks and rollouts
- Self-healing: if containers fail, Kubernetes restarts them, replaces them or kills or stops exposing them if they are not passing health-checks
- Management of secrets and configuration without the need to rebuild container images, and without exposing them

If you don't have enough capacity available to run your application, rules can be created in Kubernetes to allocate more resources. 

## Benefit from Security and Locality of an On-Premise Data Center

Many organisations don't dare (yet) to benefit from this cloud agility, because they see also a major drawback. By running applications in the cloud, also the data is hosted on this cloud infrastructure. They consider the architecture more vulnerable as they are no longer in full control of keeping the data secure from external intrusion and hacking. The question is also about responsibility in case a hacking occurs. 

Also, an on-premise data center is located physically nearby. Organisations might not want to host their application on cloud infrastructure far away, but run it on machines that are close to them or to their customers, for a few reasons: 
- Lower latencies can be expected 
- They also might want to have the infrastructure available in their local jurisdiction for legal reasons 

The Threefold Grid solves these 2 issues. 

### Local capacity

Zero-OS, the operating system that runs on Threefold Grid hardware infrastructure, is available on hardware in any form factor, and has autonomous tooling built around it. 
Consequence of this is that it can be installed outside of big hyperscale datacenters, hereby also reducing substantially the investment cost to create a data center locally. 

### Reduced hacking surface 

Many elements have been built into the technology to reduce the hacking surface around an application. See the security overview in this wiki. 
