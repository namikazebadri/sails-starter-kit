# SailsJs Docker Image

Build docker image for SailsJs application.

## Build Image
To build image run this command (__change the tag name & version with your preferred tag name & version__).

`$ docker build . -t myorganization/myimage:1.0.0`

## Running Container from Image

To create a container from the image, run this command (__change the tag name & version with your preferred tag name & version__).

`$ docker run -d -p 1337:1337 --name sails-app myorganization/myimage:1.0.0`

Then you can access the app from the browser with this url: `http://127.0.0.1:1337`

## Dockerhub image

This repository is proven by running build in Dockerhub, you can see the result [here](https://hub.docker.com/r/namikazebadri/sailsjs-app).
