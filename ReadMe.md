# KUBERNETES ESSENTIALS

## Docker Commands

- To build:

  ```
  docker build -t build-name .
  ```

- To Remove image:

  ```
  docker image rm image-name
  ```

- To kill a running container:

  ```
  docker kill image-name
  ```

- To run an existing image interactively:

  ```
  docker run -it -dp hostport:containerport build-name
  ```

- To enter a docker it session

  ```
  docker exec -it container-name/container-id sh/bash
  ```

- Create a public repository on hub.docker.com and push the image to remote repo

  ```
  docker login
  docker tag todoapp-docker:latest username/new-reponame:tagname
  docker images
  docker push username/new-reponame:tagname
  ```

- To pull the image to another environment, you can use the below command

  ```
  docker pull username/new-reponame:tagname
  ```
