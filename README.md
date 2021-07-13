# kube-infra-challenge
Kubernetes horizontal auto-scaling project

This project is developed to emulate the scenario for a deployment of an early phase of a containerized social media application using an NGINX webserver as its load balancer. The application scalability is being orchestrated by Kubernetes and the container runtime is Docker. The key features of the deployment includes a defined replica set and auto scaling based on the CPU utilization.

Operations:

- Deploy an application on Kubernetes cluster with a replica set of 3
- Create a horizontal pod autoscaler that maintains between 3 and 10
replicas of the Pods controlled by the deployment based on CPU
utilization
- Increase the load by sending a very high number of requests to the service.
- Solve underlying infra challenges by utilizing resources that are
needed at any given moment, and automatically get additional resources
when demand increases CPU utilization above 60%
