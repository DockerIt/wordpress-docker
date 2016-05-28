# WordDock

WordDock allows you to run a Wordpress site in docker with ease.

## Features
- PHP 7
- Nginx
- MariaDB

## Prerequisites

- Docker
- Docker compose
- Wordpress

## Installation
1. Download and extract Wordpress files into your project directory (but still in the wordpress folder)
2. Clone (or submodule) this repository into the project root (so there are folders `wordpress` and `wordpress-docker`)
3. `cd wordpress-docker`
4. `docker-compose up -d php-fpm nginx mariadb`

## Credits
Matthew - Tonkin - Dunn

Inspired (heavily) from the [Laradock](https://github.com/LaraDock/laradock) project created by Mahmoud Zalt.
