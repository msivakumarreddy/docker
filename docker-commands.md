# Docker commands

to check the images

```
docker images
```

Pull images from central repository

```
docker pull nginx
```

Create container out of image

```
docker create [image-id]
```

Start container

```
docker start [container-ID]
```

all the above steps in single command

```
docker run nginx
```

inspect the container

```
docker inspect [container-ID]
```

Run the container in background

```
docker run -d [container-ID]
```

Name the container

```
docker run -d --name nginx nginx 
```

Assign port number

```
docker run -d -p 80:80 nginx
```
