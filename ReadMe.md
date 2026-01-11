# KUBERNETES ESSENTIALS

## Docker Commands

- To build:
  `docker build -t build-name .`

- To Remove image:
  `docker image rm image-name`

- To kill a running container:
  `docker kill image-name`

- To run an existing image interactively:
  `docker run -it -dp hostport:containerport build-name`

- To enter a docker it session
  `docker exec -it container-name/container-id sh/bash`
