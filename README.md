# Docker image with nginx for AngularJS

This project contains the Dockerfile which run nginx and it is configured for running AngularJS applications.

** NOTE: Before compiling the Dockerfile it is necessary to copy the `app` folder of AngularJS application into this folder.**

## Build image

Run the following command to build the docker image:

```Bash
docker build -t <name of image> .
```

## Run container
Once the image is created, the following command is for run it.

```Bash
docker run -p 8080:80 -d <name of image> --name=<name of container>
```
