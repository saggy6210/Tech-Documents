# Interview Preparation

## Git Commands

## Docker

## Kubernetes
 - https://kubernetes.io/docs/concepts/overview/what-is-kubernetes/
 - Current version is v1.18
 - Previous versions are v1.17..14
 - Kubernetes is portable, extensible, open source plateform for managing containerised workload & services, that facilitate both declarative configuration and automation. 
 - Google Open-sourced the kubernetes project in 2014.
 - Traditional deployment era: Early on, organizations ran applications on physical servers. There was no way to define resource boundaries for applications in a physical server, and this caused resource allocation issues. 
 - Virtualized deployment era: As a solution, virtualization was introduced. It allows you to run multiple Virtual Machines (VMs) on a single physical server's CPU. Virtualization allows applications to be isolated between VMs and provides a level of security as the information of one application cannot be freely accessed by another application.
Virtualization allows better utilization of resources in a physical server and allows better scalability because an application can be added or updated easily, reduces hardware costs, and much more.
 - Containers are a good way to bundle and run your applications. In a production environment, you need to manage the containers that run the applications and ensure that there is no downtime.
 #### Kubernetes provides you 
 - Service discovery and load balancing
 -- Kubernetes can expose a container using the DNS name or using their own IP address. If traffic to a container is high, Kubernetes is able to load balance and distribute the network traffic so that the deployment is stable.
 - Storage orchestration 
 -- Kubernetes allows you to automatically mount a storage system of your choice, such as local storages, public cloud providers, and more.
 - Automated rollouts and rollbacks
 -- You can describe the desired state for your deployed containers using Kubernetes, and it can change the actual state to the desired state at a controlled rate. For example, you can automate Kubernetes to create new containers for your deployment, remove existing containers and adopt all their resources to the new container.
 - Automatic bin packing 
 -- You provide Kubernetes with a cluster of nodes that it can use to run containerized tasks. You tell Kubernetes how much CPU and memory (RAM) each container needs. Kubernetes can fit containers onto your nodes to make the best use of your resources.
 - Self-healing 
 -- Kubernetes restarts containers that fail, replaces containers, kills containers that don’t respond to your user-defined health check, and doesn’t advertise them to clients until they are ready to serve.
 - Secret and configuration management
 -- Kubernetes lets you store and manage sensitive information, such as passwords, OAuth tokens, and SSH keys. You can deploy and update secrets and application configuration without rebuilding your container images, and without exposing secrets in your stack configuration.
 
## Jenkins

## Linux Scripts

## Python Code

## Linux Administration 

## Networking

## Cloud - AWS/Azure/GCP
- 

## Deployment- CI/CD
