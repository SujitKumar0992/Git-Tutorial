## 1. docker version
```
docker --version
```
Example
![](./1.docker%20version.PNG)

Shows the docker version

## 2. docker images
```
docker images
```
Example
![](./2.docker%20images.PNG)

Shows the list of running containers

## 3. docker pull
```
docker pull <username>/<image>
```
Example
![](./3.docker%20pull.PNG)

it download docker image from docker hub

## 4. docker run
```
docker run -d -p Host port : Container port <Image>
```
Example
![](./4.docker%20run.PNG)
![](./5.docker%20running.PNG)

it download docker image from docker hub

## 5. docker stop
```
docker stop <container id>
```
Example
![](./6.docker%20stop.PNG)

it stops the running cointainer

## 6. docker start
```
docker start <container id>
```
Example
![](./7.docker%20start.PNG)

it start the cointainer

## 7. docker history
```
docker history <image>
```
Example
![](./8.docker%20history.PNG)

shows the history

## 8. docker inspect
```
docker inspect <image>
```
Example
![](./9.docker%20inspect.PNG)

shows low level infos in the json file format

## 9. docker rmi
```
docker rmi <image>
```
Example
![](./10.docker%20rmi.PNG)

To delete image

## 10. docker logs
```
docker logs <container id>
```
Example
![](./11.docker%20logs.PNG)

shows the log of container


## 10. docker create image
```
docker build -t <imagename> .
```
Example
![](./13.docker%20create%20image.PNG)

To create a docker image


## 10. docker push
```
docker push <username>/<imagename>:latest
```
Example
![](./14.docker%20push.PNG)

push image in docker hub










