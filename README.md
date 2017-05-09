Omeka-S in docker

There is also example of docker-compose.yml file which can be used for development.
It creates 3 containers:

- mysql db
- phpmyadmin
- omeka-s behind apache (modules or themes can be inserted via docker volumes

`docker-compose up`
