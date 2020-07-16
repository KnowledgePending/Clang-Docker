<div>
    <img src="https://github.com/KnowledgePending/Clang-Docker/blob/master/images/llvm-logo.png?raw=true"
    display="inline-block"
    margin-left="auto"
    margin-right="auto"
    width="66%" ></img>
</div>  


# [Clang Docker](https://github.com/KnowledgePending/Clang-Docker)
[![Docker Pulls](https://img.shields.io/docker/pulls/bryankp/clang.svg)](https://hub.docker.com/r/bryankp/clang)
![Docker](https://github.com/KnowledgePending/Clang-Docker/workflows/Docker/badge.svg?branch=master)



## Image details
* Ubuntu / Debian 10 Buster
* Clang 9

## Tags
* latest 
    * ubuntu with latest stable clang
* ubuntu-latest-stable
* debian-latest-stable

## Option 1. Build Docker Image
* From within the directory of the Dockerfile execute the following command to build the image
```BASH
docker build -t clang .
```
* To run with bash and a shared volume
```BASH
docker run -v <host_path>:<container_path> -ti clang:latest bash
```
## Option 2. Pull image from Docker Hub
* Go to the repository page [bryankp/clang](https://hub.docker.com/r/bryankp/clang)
* Pull the latest image
```BASH
docker pull bryankp/clang:latest
```

* To run with bash and a shared volume
```BASH
docker run -v <host_path>:<container_path> -ti bryankp/clang:latest bash
```



### Further Details
[LLVM Debian/Ubuntu nightly packages](https://apt.llvm.org/)
