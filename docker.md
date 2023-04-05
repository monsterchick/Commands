# Docker:
```
docker --help    # get whatever you want
```
## Image Commands:
<details><summary>docker pull</summary>

```
docker pull ubuntu:latest
```
</details>
<details><summary>docker images</summary>

```
docker images    # List all the images that exist locally.
```
</details>
<details><summary>docker rmi</summary>

```
docker rmi ubuntu:latest    # removes the Ubuntu image from the local machine
```
</details>
<details><summary>docker tag</summary>

```
docker tag ubuntu:latest my-ubuntu:1.0    # tags the Ubuntu image with the name "my-ubuntu" and version "1.0"
```

</details>

## Container Commands:
<details><summary>docker run</summary>

```
docker run -it ubuntu:latest bash    # creates and starts a new container from the Ubuntu image, and runs the bash command inside the container
```

</details>

<details><summary>docker ps</summary>

```
docker ps    # lists all the running containers on the local machine
```

</details>
<details><summary>docker stop</summary>

```
docker stop my-container    # stops the container with the name "my-container"
```

</details>
<details><summary>docker rm</summary>

```
docker rm my-container    # removes the container with the name "my-container"
```

</details>
<details><summary>docker exec</summary>

```
docker exec -it my-container bash    # runs the bash command inside the container with the name "my-container"
```

</details>

## Docker Compose Commands
<details><summary>docker-compose up</summary>

```
docker-compose up    # starts all the containers defined in the docker-compose.yml file in the current directory
```

</details>
<details><summary>docker-compose down</summary>

```
docker-compose down    # stops and removes all the containers defined in the docker-compose.yml file in the current directory
```

</details>
<details><summary>docker-compose build</summary>

```
docker-compose build    # builds the images for all the services defined in the docker-compose.yml file in the current directory
```

</details>
<details><summary>docker-compose logs</summary>

```
docker-compose logs -f (shows the logs for all the services defined in the docker-compose.yml file in the current directory, and follows the logs in real-time)
```

</details>
<details><summary>docker-compose exec</summary>

```
docker-compose exec my-service bash    # runs the bash command inside the container for the service with the name "my-service"
```

</details>

## Network Commands

<details><summary>docker network ls</summary>

```
docker network ls    # lists all the networks created in Docker
```
</details>
<details><summary>docker network create</summary>

```
docker network create my-network    # creates a new network with the name "my-network"
```
</details>
<details><summary>docker network connect</summary>

```
docker network connect my-network my-container    # connects the container with the name "my-container" to the network with the name "my-network"
```
</details>
<details><summary>docker network disconnect</summary>

```
docker network disconnect my-network my-container    # disconnects the container with the name "my-container" from the network with the name "my-network"
```
</details>

## Volume Commands:

<details><summary>docker volume ls</summary>

```
docker volume ls    # lists all the volumes created in Docker
```
</details>
<details><summary>docker volume create</summary>

```
docker volume create my-volume    # creates a new volume with the name "my-volume"
```
</details>
<details><summary>docker volume rm</summary>

```
docker volume rm my-volume    # removes the volume with the name "my-volume"
```
</details>
<details><summary>docker volume inspect</summary>

```
docker volume inspect my-volume    # displays detailed information about the volume with the name "my-volume"
```
</details>

## Dockerfile Instructions:

<details><summary>FROM</summary>

```
FROM ubuntu:latest (specifies that the base image for the Dockerfile is the latest version of Ubuntu)
```
</details>
<details><summary>RUN</summary>

```
RUN apt-get update && apt-get install -y nginx (runs the apt-get command inside the image to update the package list and install the nginx package)
```
</details>
<details><summary>COPY</summary>

```
COPY index.html /var/www/html/    # copies the index.html file from the current directory into the /var/www/html/ directory in the image
```
</details>
