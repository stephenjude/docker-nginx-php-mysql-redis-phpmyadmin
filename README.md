# Docker Nginx, PHP, MySQL & PHPMyAdmin

## Installation

Clone the repository

Move your source code to the app directory.

You can change mysql password inside the `conf/setup.sql`

Start all the services

```bash
docker-compose up

docker-compose exec mysql sh /conf/mysql-setup.sh
```

## Usage

Web App: `http://host_ip` or `http://localhost`

PHPMyAdmin:  `http://host_ip:8080` or `http://localhost:8080`








