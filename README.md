# Docker

## Commands
Downloads the docker image.
 ```
 docker pull image
 ```
Runs the docker image.
```
docker run image
```
Listing the running containers.
```
docker ps
```
List all the containers including the exited ones.
```
docker ps -a
```
Stops the container process
```
docker stop CONTAINERID
```
```
docker stop NAME
```
Delete a container
```
docker rm CONTAINERID
```
Listing the images
```
docker images
```
Remove image
```
docker rmi IMAGE
```
Interative mode/ terminal
 - -i  Interactive
 -  -t Terminal
 ```
 docker run -it CONTAINERID
 ```
 Run docker container in the background/in detached mode
 ```
 docker run -d CONTAINERID
 ```
 Run in attached mode
 ```
 docker attach CONTAINERID
 ```
 Mapping docker to external volume and port
 ```
 docker run -p REMOTEPORT:DOCKERPORT -v REMOTEVOLUME:CONTAINERVOLUME CONTAINERNAME
 ```
 
 [Docker+for+Beginners-Mumshad+Mannambeth.pdf](https://github.com/ngeno7/Docker/files/9291596/Docker%2Bfor%2BBeginners-Mumshad%2BMannambeth.pdf)
 
