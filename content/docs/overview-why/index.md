---
description: ''
sidebar: 'docs'
prev: '/docs/'
next: '/docs/overview-secure/'
---

# Why use TF VDC?

![](./img/vdc_node.png)

## Benefit from Agility of Cloud

TF VDC allows you to create a Virtual Data Center with a few clicks and some basic information about your requirements. It comes with tooling that is well understood in most developers' communities.

Docker containers and the orchestration of these containers by the Kubernetes framework offers the following benefits:

Containers: 
- Provides very agile application creation and deployment, with an easy and efficient creation of the container image compared to VMs
- Allows for a continuous cycle of development, integration and deployment, with quick and easy rollback
- Applications are decoupled from infrastructure, thereby isolating the development and operations concerns from each other
- Easy management of signals on application health and behavior
- Execution of an applications happens in the same way on a laptop as in the cloud
- Enables full abstraction between running an OS and running an application within this OS
- Allows for a microservices architecture, cutting applications into small, independent building blocks, which can interact in a dynamic way
- It encapsulates the application in a way that behavior at runtime becomes predictable
- An efficient use of hardware resources is possible

Orchestration through Kubernetes provides you with a lot of functionality without much effort: 
- Easily set up and manage the execution of containers and the interaction between containers
- Services to facilitate access using DNS or using IP address
- Automated load balancing in case of high traffic
- Automated rollbacks and rollouts
- Self-healing: if containers fail, Kubernetes restarts them, replaces them or kills or stops exposing them if they are not passing health-checks
- Management of secrets and configuration without the need to rebuild container images, and without exposing them

If you don't have enough capacity available to run your application, rules can be created in Kubernetes to allocate more resources. 

## Benefit from Security and Locality of an On-Premise Data Center

Many organizations don't dare (yet) to benefit from this cloud agility, because they also see major drawbacks. Considerable drawbacks are:
- Running applications in the cloud they also have to commit their data to these cloud providers and this prevents these companies from controlling and securing their data in an understood manner. 
- These companies consider cloud architectures more vulnerable to data intrusion, data theft, data ransom and other malicious practices because a cloud provider by design is a multi tenant setup. Many companies and people share the same infrastructure (servers, network, access portals etc.). Each of these shared multi tenant installations might bring security and privacy risks.
- Last but not least: who is responsibility in case data loss, data theft, or any other type of hacking occurs?

The ThreeFold Grid and the eVDC solution have an answer to the challenges and create the ability for anyone to benefit from cloud agility.

### Local secure capacity

The TF Grid is designed to create capacity everywhere: in remote places wherever a power socket meets network connectivity, or in local offices and existing data centers. It is therefore possible to create cloud infrastructure locally on site that presents the same benefits as the large scale cloud infrastructure out on the TF Grid. Even better companies can BE their own internet (cloud infrastructure).

Zero-OS is the operating system that runs on ThreeFold Grid hardware infrastructure and is available on hardware in any form factor. It is very easy to install, operates autonomously and statelessly and has incredible security and privacy features.

Zero-OS is designed to enable servers to become part of the ThreeFold grid everywhere (and owned by anyone). One key element to make this possible is to have an absolute minimal hacking surface on the physical server. In the end servers will exist in many different locations, are owned by anyone. So a key element to secure applications run on and data stored on these servers is that there is zero possibility for any human being to interact with these servers. They do not have a login facility, they do not store and access credentials, they have no interface for people to interact in any possible way with these servers.
