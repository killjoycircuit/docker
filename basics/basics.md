## docker notes
- images →Docker images are versioned ,different versions are identified by tags, each can contain multiple image layers
- container → instance of a image, we can built multiple containers from image
- docker registry→ provides storage and distribution system services for docker images 
- docker repository → collection of related images with diff verions
- port binding →application inside conatiner runs in an isolated docker network, we need to expose the container port to the host,binding the container port to the host port to make the service available to outside world 
- Dockerfile → txt document that contains commands to assemble an image then docker can build n image by reading those instructions 
- It starts from a parent image/base image, you choose the base image depending on which tools you need to have available
- Struture:
FROM 
COPY
WORKDIR
RUN
CMD

- each instruction in it creates a layer , which are stacked and each one is delta of changes in prev layer 


