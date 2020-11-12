# dockerfile-demo

A few simple demos on how to build Docker images using Dockerfile or docker-compose.
In the directories listed below, you will find:

## Docs

The slides and a text file with the commands used to build the images.

## Prerequisites

A running Dokcer Desktop install with linux containers and an IDE. It was tested on Windows with Visual Studio Code.

## Demo 1

The simplest Dockerfile, using Busybox. Execute a command to create a file in the new image, using FROM and RUN.

## Demo 2

Based on PHP/Alpine, build a single file PHP app that echoes "Hello world", and add the COPY and CMD commands to the picture.

## Demo 3

Demo 2, but demonstrating the use of docker-compose to build the image.

## Demo 4

Add Xdebug to PHP to demonstrate a more elaborated use of CMD to avoid generating unnecessary layers. The PHP app echoes the name passed in parameters.

## Demo 5

A more elaborated Docker file, demonstrating ENV and WORKDIR in addition to the previous commands. The app and Dockerfile are the demo example of the Docker "Get started" documentation for images (see: https://docs.docker.com/get-started/nodejs/build-images/)
