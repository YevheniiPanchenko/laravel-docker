## How To Set Up Laravel, Nginx, and MySQL with Docker Compose

## Prerequisites 

One Ubuntu 18.04 server, and a non-root user with sudo privileges. Follow the Initial Server Setup with Ubuntu 18.04 tutorial to set this up.

Docker installed?n Ubuntu 18.04.

Docker Compose installed, on Ubuntu 18.04.

https://www.digitalocean.com/community/tutorials/how-to-set-up-laravel-nginx-and-mysql-with-docker-compose

## Changes 

1. Docker’s composer image 
docker run --rm --interactive --tty \
  --volume $PWD:/app \
  composer install

2. Dockerfle
... \
nano

3. Permission
sudo chmod 777 -R storage/
sudo chmod 777 -R bootstrap/cache/
sudo chmod 777 .env
