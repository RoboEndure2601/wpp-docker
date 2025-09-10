# WPPConnect Team

## *Wppconnect Docker*

Easily create Docker images with different versions/combinations of languages and common dependencies, for use with WPPConnect.

## Our online channels

[](https://discord.gg/JU5JGGKGNG)
[](https://t.me/wppconnect)
[](https://chat.whatsapp.com/LJaQu6ZyNvnBPNAVRbX00K)
[](https://www.youtube.com/c/wppconnect)

## Requirements

  * Docker [3.x](https://www.docker.com/get-started) or newer.

## Installation

Download the folder corresponding to the tutorial below to install:

### Docker \#1: Deploying the Server and Front-end using Containers.

  - Tutorial on the YouTube Channel: https://www.youtube.com/watch?v=TQJ4ID1vs\_c
      - Folder: [docker-server-front](https://www.google.com/search?q=./docker-server-front)

### Docker \#2: Setting up a development environment for WPPConnect.

  - Tutorial on the YouTube Channel: https://www.youtube.com/watch?v=kDHbf1TWkBw
      - Folder: [docker-server-front-dev](https://www.google.com/search?q=./docker-server-front-dev)
          - Use the configuration files from the previous tutorial ([Docker\#1](https://www.youtube.com/watch?v=TQJ4ID1vs_c)) and create the "/app" folder with the current version of the repositories ([wppconnect-server](https://github.com/wppconnect-team/wppconnect-server) and [wppconnect-front](https://github.com/wppconnect-team/wppconnect-frontend)) inside their respective applications.

### Docker \#3: Raising everything with just one command line using the server-cli

  - Tutorial on the YouTube Channel: [https://www.youtube.com/watch?v=zBmCnPS3JOQ](https://www.youtube.com/watch?v=zBmCnPS3JOQ)

### Docker \#4: Setting up an https certificate for localhost.

  - Tutorial on the YouTube Channel: [https://www.youtube.com/watch?v=Mk0sIYJ6peE](https://www.youtube.com/watch?v=Mk0sIYJ6peE)

### Docker \#5: Setting up 5 WPPConnect Servers with load balancing using Nginx.

  - Tutorial on the YouTube Channel: [https://www.youtube.com/watch?v=nfc-yDrtnMQ](https://www.youtube.com/watch?v=nfc-yDrtnMQ)
      - Folder: [docker-server-load-balancing](https://www.google.com/search?q=./docker-server-load-balancing)

### Docker \#6: Setting up the WPPConnect Server with Chatwoot using Nginx.

  - Tutorial on the YouTube Channel: https://www.youtube.com/watch?v=00616mTid-M
      - Folder: [docker-server-chatwoot](https://www.google.com/search?q=./docker-server-chatwoot)

### Docker \#7: Using the PHP + MySQL + phpMyAdmin + Nginx Client with the WPPConnect Server.

  - Tutorial on the YouTube Channel: https://www.youtube.com/watch?v=o\_TBIyxFbNI
      - Folder: [docker-server-php-mysql-dev](https://www.google.com/search?q=./docker-server-php-mysql-dev)

## Roadmap (Next Videos/Tutorials)

  - Docker \#8: Configuring the Laravel Client to consume the WPPConnect endpoints.

## Commands Used

Compiles, (re)creates, starts, and attaches a container to a service:

```bash
$ docker-compose up --build --no-start
```

Stops and removes all container(s) and network(s):

```bash
$ docker-compose down
```

Starts the container(s):

```bash
$ docker-compose start [servicename...]
```

Stops the container(s):

```bash
$ docker-compose stop [servicename...]
```

Lists the images used by the created containers:

```bash
$ docker images
```

Views the logs of the containers.

```bash
$ docker logs [servicename...]
```

Views the statistics of the containers such as: cpu, memory consumption, etc...

```bash
$ docker stats [servicename....]
```

Deletes all processes/services from the local computer:

```bash
$ docker rm $(docker ps -a -q) -f  
```

Deletes all images from the local computer:

```bash
$ docker rmi $(docker images -a -q) -f
```

Removes the builder's cache:

```bash
$ docker builder prune
```

Removes unused networks:

```bash
$ docker network prune
```

Access the [link](https://docs.docker.com/reference/) to see all Docker commands.

## Postman

Access the [WPPConnect Postman Collection](https://documenter.getpostman.com/view/9139457/TzshF4jQ) with all endpoints.
