# wordpress-mysql-containers
Deploy a fully functional wordpress site with docker containers in less than one minute.

## Parameters

- MYSQL_PASSWORD: change this value to your preferred password.
- MYSQL_ROOT_PASSWORD: change this value to your preferred password.
- WORDPRESS_DB_HOST: use a static IP. In case you test this environment on your local docker installation you can leave `host.docker.internal` value.


## Deployment

Run docker compose file `docker compose up -d`
