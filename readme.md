## Introduction
This is a Dockerfile to build a container image for nginx and php-fpm for talaria projects

## Git repository
The source files for this project can be found here: https://github.com/mozose/docker-nginx-php

## Pulling from Docker Hub
Pull the image from docker hub rather than downloading the git repo. This prevents you having to build the image on every docker host:

```
docker pull mozose/docker-nginx-php
```

## Running
To simply run the container:

```
docker run --name nginx -p 8080:80 -d mozose/docker-nginx-php
```

You can then browse to http://DOCKER_HOST:8080 to view the default install files.
