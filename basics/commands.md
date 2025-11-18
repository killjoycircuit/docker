## commands

- ```docker images``` → list of all docker images 
- ```docker ps ```→ list running containers 
- ```docker ps -a``` →list all the running containers 
- ```docker pull {name}:{tag}``` →pull image from registry(without braces )
- ```docker run {name}:{tag}``` →creates a container from given image and starts it (without braces)
- ```docker run -d {name}:{tag}``` →creates a container that runs in bg from given image and starts it (without braces)
- ```docker stop {containerid} ```→stop a container
- ```docker run -d -p {host port}:{container port} {name}:{tag}``` →binds port 
- only one service can run on a port 
- its standard is to use same port as one container uses
- ```docker run``` → runs a new container every time not reuses prev ones 
we can also name our container
- ```docker build``` → to build images of a project
