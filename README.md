# Infrastructure Tutorial

 ✅ **Technical Requirement**
 1. Macbook
 2. The latest version of Docker, version *** at the time we write the turorial 
 3. The latest version of  Docker compose, version *** at the time we write the turorial 
 4. accesss to bash in terminal
 
 
## Setup Docker 
Environment and setup before setting up docker. 

### Download 

**Option 1** 

Download Docker desktop by running the following:

1. Download the Package Manager *homebrew* for MAC.  -- skip if already download 
```
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

Please refer to the [installation page](https://brew.sh/)

2. Download the docker desktop software by using brew install command. 

```
brew install --cask docker
```


**Option 2** 

1. Install Docker Desktop: Download Docker Desktop for Mac from the official website (https://www.docker.com/products/docker-desktop) and follow the installation instructions.

2. Start Docker Desktop: Once the installation is complete, start Docker Desktop.


### Verification 
Verify Docker Installation: Open the terminal and run the following command to verify that Docker is installed and running:
```
docker run hello-world
```

The result you should see after successfully pull the hello-world image.
```
Hello from Docker!
This message shows that your installation appears to be working correctly.
```

### Introduction to Docker

**Note:**

Docker is an open-source platform that enables developers to automate the deployment, scaling, and management of applications inside containers. 
Docker's architecture is built on top of Linux Containers (LXC), which provides a secure and isolated environment for applications to run. Docker containers are isolated from each other and from the host operating system, making it easier to manage applications and ensure their security. Additionally, Docker images are created from a set of instructions called a Dockerfile, which makes it easier to automate the build and deployment process.

**Basic Commands**
Here are some of the most commonly used Docker commands:

1. docker run: This command is used to run a Docker container. You can specify the image to use, set environment variables, and configure other options when running a container.

2. docker ps: This command is used to list the containers that are currently running. It displays information such as the container ID, image name, status, and ports. Note: docker ps -a will display all the previous containers. 

3. docker images: This command is used to list the Docker images that are available on the system. You can use this command to see the size of each image, when it was created, and other metadata.

4. docker pull: This command is used to download a Docker image from a registry, such as Docker Hub. You can specify the image name and optionally the version to pull.

5. docker stop: This command is used to stop a running container. You can specify the container ID or name to stop.

6. docker rm: This command is used to remove a Docker container. You can specify the container ID or name to remove.

7. docker exec: This command is used to run a command in a running container. You can specify the container ID or name and the command to run.

8. docker build: This command is used to build a Docker image from a Dockerfile. You can specify the path to the Dockerfile and the name and tag for the resulting image.

Please explore the [tutorial sections](https://docs.docker.com/get-started/) of docker to familiarize yourselves with those commands



## Setup MLFlow in Docker






## Setup postgresSQL in Docker


## FAQ

