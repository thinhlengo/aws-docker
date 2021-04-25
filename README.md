AWS and Docker image
=========================================

This image additional aws and docker plugin dependent GNU C library (glibc).
This repository forked from [docker-alpine-glibc](https://github.com/Docker-Hub-frolvlad/docker-alpine-glibc) and then added aws and docker for purpose CI/CD


Usage Example
-------------

Build image:
```sh
$ docker build -t aws-docker .
```

Test image:
```sh
$ docker run aws-docker aws --version
```
