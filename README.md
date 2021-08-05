# docker-commands
List of docker commands


### Docker run, Under the hood *run* command is combination of two commands *docker create* and *docker start*
*docker create* commands creates the container while *docker run* command runs the container.
> docker run <image-name>

### To list running continers
> docker ps
### To list all containers ever created running as well as stopped
> docker ps --all

### Starting docker container 
> docker create <container-name>

### Starting docer container
> docker start <container-id>

### Attaching logs to container
> docker start -a <container-id>

### To delete all container
> docker system prune

### To print container logs
> docker logs <container-id>

### To stop docker container
> docker stop <container-id>
*Docker stop waits for 10 seconds befire killing the container. It gives time to process to shut down gracefully and then it kills the contianer*

### To kill docker container
> docker kill <container-d>
*Docker kill will immidiately kill the container. This is not recommended*	



> docker run <image_name:version>
### How to run command inside image alongwith run command if commands avaiable in image eg. ls,echo command
> docker run <image_name:version> ls
> docker run <image_name:version> echo hello





## Container Commands

