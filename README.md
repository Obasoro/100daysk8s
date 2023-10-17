#### 100 days Kubernetes

#### Text Books and materials used

- [ ] Kubernetes Up and Running

- [ ] 50 Kubernetes Concept Every DevOps engineer should Know

- [ ] Kubernetes Best Practices

- [ ] Cloud Native Devops with Kubernetest

I would be sharing details base on Books used as as a Branch on this repo

Let's try out Terraform
Install Terraform
Initialise cloud provider
Run "terraform init"
Set-up a security group
Make sure that you set up the file
Try whether or not it works with "terraform plan" . Here we would expect something to add but 
not necessarily something to change or to destroy.
Don't display your credentials openly, you would probably want to use something like Ansible 
vault or similar to store your credentials, do not store in plain text
Once we have finished setting up our resources, we want to destroy them "terraform destroy"

### Networking

*clusterIP* is used by default and allows communication between cluster

*NodePort* Allows for communication outside access

*LoadBalancer* is useful for routing traffic between containers within pods

- First, 

### Service Mesh
 - A service mesh is an infrastructure layer in your application that facilitates communication between services. Service mesh provides capabilities like traffic management, resiliency, policy, security, strong identity, and observability to your workload. Your application. Service mesh allow ensures that communication among containerized and often ephemeral application infrastructure services is fast, reliable, and secure. It provides service discovery, load balancing, encryption, observability, traceability, authentication and authorization, and support for the cirt]cuit breaker pattern

 ### Scenario
 - Encrypting all traffic
 - Canary and phase rollout
 - Traffic management and manipulation
 - Observability

 Before selecting *service mesh* have a good understanding of your requirement for installing a service mesh.

 - is an ingress controller sufficient for my needs
 - can my workload and environment tolerate additional overheads
 -

 [Microsoft](https://learn.microsoft.com/en-us/azure/aks/servicemesh-about) 
 [Nginx](https://www.nginx.com/blog/what-is-a-service-mesh/)

 ### Cloud-native DevOps for DevOps

 Understanding the resource usage in Kubernetes is essential


