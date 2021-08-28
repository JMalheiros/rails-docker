# RAILS-DOCKER

This is a empty RoR project with Docker, Docker-Compose, Redis and Sidekiq. Just a sample to new projects.

## Especifications

This project has the following tecnologies and versions:
        - Ruby: 3.0.2
        - Rails: 6.1.4
        - Bundler: 2.1.4
        - Docker: 20.10.8
        - Docker-compose: 3.4
        - Nodejs: 11.15.0
        - Sidekiq: 6.2.1
        - Redis: 4.4.0

## How to start it

To use this sample project, first you need to clone the repository into a new directory called rails-docker

        $ git clone https://github.com/JMalheiros/rails-docker.git rails-docker
        
Then, enter the respository and create your own .env

        $ cd rails-docker
        $ cp .env.sample .env

Use the deafult enviroment variables or put yours:
        - DATABASE_NAME: Name of your database
        - TEST_DATABASE_NAME: Name of your test database
        - DATABASE_USER: Name of your database
        - DATABASE_HOST: Name of your host
        - REDIS_HOST: Name of your redis host

If you put your own database variables, update the init.sql with the new username

Finally, build and start the containers

        $ docker-compose up -d --build
## Database creation and settings

## About the test suite
