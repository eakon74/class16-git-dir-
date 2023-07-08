# Home work assignments

Nginx container 
507326064fa8   nginx:lates

MySQL Container 
b419fdd12d64   mysql:latest

Difference between repository/registry
A container repository: is a collection of related container images that provide different versions of an application, allows you share container images with your team, customers, or the community at large
A container registry: is a collection of repositories that store container images. A server side application that stores and lets you distribute Docker images

I signed up for docker hub

Docker main Commands
FROM: set the image that will be used as base in our image.
ADD: To move a file into a container directory, it can be .tar files.
CMD: defines a command to be executed when a container with this image initializes.
LABEL: Use it to set a container's description and keep it easy to manage all containers.
COPY: Similar to ADD, but you can copy normal files and directories.
ENTRYPOINT: It's like CMD, but this cannot be overwritten, it will always execute, the container will run as an executable. When this command dies, the container dies too.
ENV: Sets environment variables to the container
EXPOSE: Sets ports that container will expose, so that container will be accessible by these ports
RUN: Used to run commands in the container, generally used to install packages.
USER: define a user inside the container, the default is the ROOT user.
WORKDIR: Defines the directory of work.
VOLUME: Creates a volume, a directory that will have a copy in our machine/host-docker.
MAINTAINER: Set the container owner.
Build container:  Docker build command.








