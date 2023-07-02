# laravel-docker-setup
simple laravel docker set based on a digital ocean example

## whats in it
- [x] separate nginx and fpm containers
- [x] separate networks for API and WEB context
- [x] mailhog for testing emails

## installation


1) clone the project
```
$ git clone https://github.com/HijenHEK/laravel-docker-setup.git
```
2) copy files to your project directory
```
$ cp -r laravel-docker-setup <your-laravel-project-directory>
```
3) add the env variable to your .env or use default values
```
SERVER_USER
SERVER_USER_UID
DB_DATABASE
DB_PASSWORD
DB_PASSWORD
DB_USERNAME
FORWARD_DB_PORT
APP_PORT
MAIL_PORT
MAILHOG_PORT
```
4) build and create your containers
```
$ docker-compose up -d --build
```
