# WordPress Docker

WordDock allows you to run a WordPress site in docker with ease.

## Features
- PHP 7
- Nginx
- MariaDB

## Prerequisites

- Docker
- Docker compose
- WordPress

## Installation
1. Download and extract WordPress files into your project directory (but still in the `wordpress` folder)
2. Clone (or submodule) this repository into the project root (so there are folders `wordpress` and `wordpress-docker`)

        git clone https://github.com/DockerIt/wordpress-docker

    or if you are already using version control:

        git submodule https://github.com/DockerIt/wordpress-docker

3. `cd wordpress-docker`
4. `docker-compose up -d php-fpm nginx mariadb`
5. You should then be able visit the site by visiting the IP address
    - Windows: Type `docker-machine ip`
    - Linux: 127.0.0.1
6. Use a nice URL, edit your hosts file and put the IP address in your hosts file.
7. When you go through the WordPress 5 minute install the only thing you need to change is the Database Host to `mariadb`

## Credits
Matthew Tonkin - Dunn

Inspired (heavily) from the [Laradock](https://github.com/LaraDock/laradock) project created by Mahmoud Zalt.
