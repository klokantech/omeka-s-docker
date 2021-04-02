Omeka-S in docker (version 2.0 agosto 2019)

There is also example of docker-compose.yml file which can be used for development.
It creates 3 containers:

- mysql db
- phpmyadmin
- omeka-s behind apache (modules or themes can be inserted via docker volumes

`docker-compose up`


To build the image 
docker build -t "name"

docker images  

docker-compose up 

Updated DOCKER IMAGE in https://hub.docker.com/r/horaciod/omekasid




