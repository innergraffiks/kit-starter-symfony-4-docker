# kit-starter-symfony-4-docker
🏁 The perfect kit starter for a Symfony 4 project with Docker and PHP 7.2

# First : Init your Docker
You have to install [Docker CE](https://docs.docker.com/get-started/#images-and-containers) on your local desktop.

# Installation
## GIT
Clone this [project](https://github.com/innergraffiks/kit-starter-symfony-4-docker.git) from GitHub

## Symfony project
Create file `docker-compose.override.yml` at the root of this Docker project and copy this inside :

    version: '3'
    services:
        server:
            volumes:
                - ~/projects/sf4:/home/wwwroot/sf4
                
Replace path `~/projects/sf4` by your Symfony 4 project path on your local desktop.
