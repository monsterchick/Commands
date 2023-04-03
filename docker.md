# Docker
```
docker ps -a    # Shows all Docker containers, both running and stopped.
``
```
docker ps -a    # Shows all Docker containers, both running and stopped.
```
```
docker images    # Lists all available Docker images.
```
```
docker rm container_id    # Deletes a Docker container.
```
```
docker rmi image_id    # Deletes a Docker image.
```
```
docker start/stop container_id    # Starts or stops a Docker container.
```
```
docker run --name container_name -dit image_id    # Creates a new Docker container with a specified name and runs it in detached mode.
```
```
docker exec -it container_id command    # Runs a command inside a running Docker container, with an interactive terminal.
