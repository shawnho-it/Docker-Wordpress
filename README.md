# terraform-aws-basic
The goal of this project is to spin up Wordpress, alongside MySQL 5.7 & Nginx for reverse proxy, using [Docker](https://docker.com).

## Configurations
This code will spin up 3 containers, namely:
1. Wordpress
2. MySQL:5.7
3. Nginx

The purpose of this code is to simulate a basic working infrastructure of hosting a local Wordpress site with Nginx for reverse proxy for security purposes.

## Usage
1. Clone all the files in a directory
2. Put your own IP address in nginx.conf/default.conf.
3. cd to the directory with the docker-compose.yaml file.
4. Run "docker-compose up -d".
5. Visit your IP address in a browser.

NOTE: Your must have docker & docker-compose installed.
