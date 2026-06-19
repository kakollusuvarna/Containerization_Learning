
Kubernetes Basics

Before knowing Kubernetes we should understand about containers and Docker.

Container:
Introduction -
In real world it advanced from (Physical servers --> VM--> Containers)
 
  Hypervisor is a virtualization platform thats creates and manages(basically seperates and creates indvidually as per snippet below) applications and its OS- each application has its own OS and highly secure and it is Good.

<img width="301" height="225" alt="Image" src="https://github.com/user-attachments/assets/146f0b2e-82b0-49f4-a923-ed292eb5e295" />


But it can be like we are not using complete resources- for example if an organization bought 1000 GB phyiscal server and installed Hypervisor and it is 
divided into different VM but the organization will not use complete resources.

So we should now understand, why we moved to containers-- same thing as above we are not using full capacity of the resources as some apps need only less resources even though they are running on full fledged mode, like it can only use 20 or 30 GB even though the VM has 100 GB space. so here we are wasting some resources.

So containerization will solve some problems of virtualization - not all as Virtualization is more secured when compared to containerization because they are strictly isolated where as container can talk to other containers and there will be some sort of leakage.

Containerzation can be done in two ways:

1- it can be done on top of physical server.
2- it can be done on top of VM or EC2 -- this is through some cloud provider and most commonly used as there wont be any additional maintainence or adminstrator required.

<img width="712" height="441" alt="Image" src="https://github.com/user-attachments/assets/8698c22b-94ea-4d6d-a741-95e25f01bfd9" />


Docker:  

Docker images are very light weight reasons:
- No full OS for each container- uses OS from base image OS
- It packages app and its depndencies and share the common Host
- easy to ship
  

