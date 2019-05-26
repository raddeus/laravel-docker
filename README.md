# Laravel 5 Docker Template

A barebones template to run Laravel 5 in development

## Installing

Move the `docker` folder, `.env.docker` and `docker-compose.yml` into your project.

Change `app-name` to whatever you want your database name to be in `.env.docker` and `docker-compose.yml`.

Move the configuration lines in `env.docker` to your existing `.env`
## Running

`docker-compose up -d`

## Executing artisan/composer commands

`docker-compose exec app bash`

This opens a bash session on the app container, where you will have access to composer and artisan

`composer install`

`php artisan migrate`







