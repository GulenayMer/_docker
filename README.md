# _docker
System Administration by using Docker 

This project aims to broaden the knowledge of system administration by using Docker.
 Several Docker images are virtualized && created in virtual machine.
 
 + The Makefile sets up the entire application (it builds the Docker images using docker-compose.yml)
 + Dockerfiles are written, one per service.
 + The containers are built from the penultimate stable version of Alpine
 + Each service runs in a dedicated container. 
 + A Docker container that contains WordPress + php-fpm (it is installed && configured) without nginx.
 + A Docker container that contains MariaDB without nginx.
 + A volume that contains the WordPress database.
 + A second volume that contains the WordPress website files.
 + A docker-network that establishes the connection between the containers.
 + Redis cache is set up for the WordPress website in order to properly manage the cache.
