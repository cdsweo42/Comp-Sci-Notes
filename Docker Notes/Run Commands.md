## Docker Run Commands
-	`docker run (image name):(tag)` pulls an image of a specific version and runs that. If no tag is specified, then the latest version will be selected
### STDIN
Docker containers, by default, do not have a STDIN, even if you're attached to the console.
- `docker run -i (container)` maps the STDIN to the docker container. Stands for interactive mode.
- `docker run -it (container)` maps the STDIN to the docker container and attaches to the container's terminal. Stands for pseudo terminal.
### Port Mapping
`docker run -p (docker host port):(docker container port)`: maps a port on the docker host to the port on the docker container so that users outside the docker container can access the application
### Volume Mapping
`docker run -v (docker host directory):(docker container directory)` implicitly mounts the external directory to a folder inside the docker container. All data will now be stored in the outside directory. All data will be safe if the container is deleted now.
### Inspect Containers
`docker inspect (container)` returns all details of a container in a json format
### Container Logs
`docker log (container)` views logs, or everything displayed to the STDOUT of the container