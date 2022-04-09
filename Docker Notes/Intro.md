## What is Docker?
Docker packages and containerizes applications and allows them to run anywhere.
### VMs vs. Docker
![[containers-vs-virtual-machines.jpg]]

- Docker containers use much less resources than VMs because VMs add additional OSes on top of the kernel. 
- More resources are shared between docker containers and VMs are completely isolated from eachother.
### Containers & Virtualization
Containers and Virtualization should be utilized together for large enterprise applications in order to easily manipulate sets of containers while leaving others untouched.
### Image vs. Container
- Image: a package or template used to create one or more containers
- Containers: run instances of images that are isolated with their own set of processes and have their own environments
### Docker Images
Go to:
> https://hub.docker.com/

This link contains information about all docker images such as versions.