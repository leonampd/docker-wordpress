## Docker-compose WordPress Environment

This project intent is to provide an easy way to run an wordpress instance for theme/plugin development

## Running a new WordPress instance

- Clone this repo
- Edit the `.env` file defining environment variables as you can see on [WordPress docker Official image](https://hub.docker.com/_/wordpress/) and [MySQL Docker official imagem](https://hub.docker.com/_/mysql/)

## Defining WordPress and MySQL tag images

This project has a `docker-compose.yml` that uses environment variables to set the tag images: `WORDPRESS_TAG` and `MYSQL_TAG`. It permit to change wordpress, php and mysql versions without need to edit the `docker-compose.yml`
