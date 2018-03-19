# Docker hand-on App
This app can be used as an exaple for getting a hands on all docker service.
This uses a Dockerfile to build a image and a docker-compose.yml for building a stack.

To run this install Docker from here https://docs.docker.com/install/

To build the image :

### docker build -t <image_name_tag> .

To run the image

### docker run -d -p 8080:80 --name <container_name> <image_name_tag>

To build using docker-compose:

### docker-compose up
