# Docker-Compose-WordPress
This docker-compose runs WordPress with a MySQL DataBase, using PHP 7.2 and phpMyAdmin, adding volumes to store the DataBase data and wp-content.

## How to start on a local

Requirements
- Docker

## Clone the reposiory and run 

### `docker-compose up`

This will install dependencies and start a service on port 8080 to WordPress and 8081 to phpMyAdmin

Variables to add to docker compose
```
WORDPRESS_DB_HOST:
WORDPRESS_DB_USER:
WORDPRESS_DB_PASSWORD:
WORDPRESS_DB_NAME:

MYSQL_DATABASE:
MYSQL_ROOT_PASSWORD:
```
