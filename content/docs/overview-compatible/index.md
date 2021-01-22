---
description: ''
sidebar: 'docs'
prev: '/docs/overview-independent/'
next: '/docs/start-how/'
---

# IT-Standard Compatibility

The IT industry is used to standard tooling for the deployment of their IT workloads: 
- Docker is the standard for container
- K8s is the standard for container orchestration
On the TF Grid a Kubernetes orchestrator can be deployed out of the box. We have implemented the [K3S](https://k3s.io) implementation, which is a full-blown Kubernetes offering, but using only half of the memory footprint. It is packaged as a single binary and made more lightweight so that it can run in resource-constrained locations (so fit for IoT, edge, ARM etc).
- For storage, any file system will be supported 

The process for deploying workloads has been made easy with many Helm templates already available, ready for usage on the grid.
