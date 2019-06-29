# dclong/nodejs [@DockerHub](https://hub.docker.com/r/dclong/nodejs/) | [@GitHub](https://github.com/dclong/docker-nodejs)

NodeJS in Docker.

## About the Author

[Personal Blog](http://www.legendu.net)   |   [GitHub](https://github.com/dclong)   |   [Bitbucket](https://bitbucket.org/dclong/)   |   [LinkedIn](http://www.linkedin.com/in/ben-chuanlong-du-1239b221/)

## Usage in Linux/Unix

```
docker run -d \
    --log-opt max-size=50m \
    -e DOCKER_USER=`id -un` \
    -e DOCKER_USER_ID=`id -u` \
    -e DOCKER_PASSWORD=`id -un` \
    dclong/nodejs
```
```
docker run -d \
    --log-opt max-size=50m \
    -e DOCKER_USER=`id -un` \
    -e DOCKER_USER_ID=`id -u` \
    dclong/nodejs
```
