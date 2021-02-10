# A Cloud9 docker image based on Ubuntu 16.04 (Xenial)

## Base Docker Image
[Ubuntu](https://hub.docker.com/_/ubuntu) 16.04 (x64)

## Get the image from Docker Hub or build it locally
```
docker pull fullaxx/cloud9-xenial
docker build -t="fullaxx/cloud9-xenial" github.com/Fullaxx/cloud9-xenial
```

## Run the image on port 80
```
docker run -d -p 80:80 fullaxx/cloud9-xenial
```

## Save your Cloud9 workspace on the host
```
docker run -d -p 80:80 -v /your/path/c9ws/:/c9ws/ fullaxx/cloud9-xenial
```
