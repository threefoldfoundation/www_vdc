---
description: ''
sidebar: 'docs'
prev: '/docs/overview-independent/'
next: '/docs/start-how/'
---

# IT-Standard Compatibility

The IT industry is used to standard tooling for the deployment of their IT workload: 
- Docker is the standard for container
- K8S is the standard for container orchestration
On the TF grid a Kubernetes orchestrator can be deployed out of the box. We have implemented the [K3S](https://k3s.io) implementation, which is full-blown Kubernetes offering, but using only half of the memory footprint, packaged as a single binary and made more lightweight so that it can run in resource-constrained locations (so fit for IoT, edge, ARM etc). 
- Simple Storage Service (S3) is the standard for storage, giving developers a means to control data using a rich API set

The process for deploying workloads has been made easy as quite a lot of Helm templates have been made available, ready for usage on the grid. 

<img src="./img/docker.png" alt="drawing" height="100"/> <img src="./img/kubernetes.png" alt="drawing" height="100"/>
