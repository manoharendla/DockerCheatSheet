# Welcome to Docker cheat Sheet


| S.No. | Dockercommand | Description | 
| --- | --- | --- |
| 1. | docker images | Displays the images in the docker host |
| 2. | docker build -t="sampleTagName to Identify your image created using docker file" | When docker build is executed in the directory where the docker file is available, an image will be created with the definitions created in the docker file |
| 3. | docker jenkins pull | Pulls a Jenkins image from the docker cloud repository or docker hub  |
| 4. | docker stop containerId(or)ContainerName | Stops the running container using SIGTERM and then SIGKILL, helps in gracefull shutdown of the container |
| 5. | docker kill jenkins | Stops a container without a gracefull shutdown, chances of unstable state of the container |
| 6. | docker run imageName | Creates a container from the image |
| 7. | docker run -it imageName /bin/bash | Creates a container in interactive mode and executes the command /bin/bash as an entry point |
| 8. | docker run --name="CreateANameforContainer" imageName  | Creates a container with specified Name |
| 9. | docker run -d imageName  | Creates a container in detached mode |
| 10. | docker attach containerName  | Allows you to attach to the container in interactive mode |
| 11. | docker ps  | Lists the running containers |
| 12. | docker ps -a  | Lists all the containers in running or exited state |
| 13. | docker inspect container  | Lists all the containers in running or exited state |
| 14. | docker run --help  | Lists all the available commands with run |
| 15. | docker start containerName  | Start a container that is in existed ot stopped state |
| 16. | docker exec -it containerName bash | Connect interactively through terminal or ssh into running container |
| 17. | docker ps -s | Retrives the size used by the container and also displays the virtual size which is equivalent to size of reaonly image size and contianer size|
| 18. | docker port containerID | list downs all the ports used/exposed by the running container |
| 19. | docker run -dit imageName | Runs the container in daemon mode |
| 20. | docker run -dit --publish-all imageName | publish all the ports defined in an image . Note: Difference between Publish and expose, expose allows the ports to be visible for inter communicaiton between containers and publish allows you to reach the port from host |
| 21. | DOCKER_OPTS="--iptables=true --icc=false" | If you want to restrict the communication between the containers add the line to /etc/default/docker for ubuntu | 




| S.No | Details of commands used in Dockerfile | Description  |
| --- | --------------------------------------- | ----- |
| 1. |  ENV var1=Mano var2=Master |  Using ENV keyword we declare variables |
| 2. | WORKDIR dirname | Set the Working directory when the container is launched |
| 3. | CMD pwd |  Execute a command when container is launcher |
| 4. | FROM ubuntu | Base image |
| 5. | MAINTAINER  manoharendla277@gmail.com | Helps in dentifying the  owner of the image file |


