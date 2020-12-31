---
description: ''
sidebar: 'docs'
prev: '/docs/overview-why/'
next: '/docs/overview-decentralized/'
---

# Why is TF VDC so secure?

## Running on an OS with no hacking surface

Zero-OS is the operating system that runs on the Threefold nodes. All weaknesses of an operating system with regard to hacking have been considered in the implementation of this peer-to-peer OS. 
- It has no shell, meaning that farmers, i.e. owners of the capacity that hosts the OS and the workloads, have no access to the data residing nor the applications running on their hardware. 
- The management of the grid and the workload running on it is not in the hands by humans, hereby excluding both human error and malicious hackers. Bots take over this role: we have defined the concept of a 3Bot as a human's virtual system administrator. How this exactly works can be read below in the deployment process security. 

## Network security

- All networking in Zero-OS comes is set up as a private overlay network. All nodes have their own IPv6 address and are fully interconnected in the defined network. All traffic on the network is encrypted.  
- The link to the outside world is managed through the web gateways. These web gateways filter out incoming traffic, only allowing external traffic that is accepted from inside. 
- There is no TCP/IP traffic allowed coming from the outside. Data is picked up from the inside. 

## Quantum-secure Storage 

We have developed the service to have S3 storage split in an intelligent way into different shards, in a way that on one location, there is only part of the information stored in one place. Moreover, the data is described in a descriptive way so that a person aiming to hack into the low-level data (which is almost impossible in itself), will only find non-relevant information on this storage infrastructure. 
The fact that no data shard can be created only accessing one location, makes the storage quantum proof: no compute power can ‘imagine’ what these missing data are. 
More info on our dispersed storage mechanism can be found [here](https://manual.threefold.io/#/architecture_storage?id=dispersed-storage-architecture-design-philosophy). 

This secure storage has been implemented into Minio S3 storage offering, available on the Threefold Grid. 

## Security in the deployment process

Deployment of IT workload using a so-called “Smart Contract for IT” makes the deployment process resilient to human error and hacking. The system is self-driving and self-healing, therefore removing the human requirement for deploying and operating IT infrastructure and services. This represents a breakthrough in IT. 3Bot records all transactions within the blockchain database (BCDB), ensuring an immutable record of any workload and enables the self-healing functionality as any workload can easily be restored if/when needed.


## Fully decentralized access

Access to your virtual data center happen through Threefold connect app. This app is a fully decentralized authentication mechanism, based on PKI technology. 

![](./img/vdc_secure.png)
