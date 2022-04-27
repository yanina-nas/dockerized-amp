# dockerized-amp
Docker setup setup for running a multi-container application (Apache 2.4, MariaDB 10.4, PHP 8.1 (as in XAMPP for Windows 8.1.5 / PHP 8.1.5) locally.

1. Make sure that [Docker desktop](https://www.docker.com/products/docker-desktop/ "download Docker desktop") is installed and running

2. All php code that you wish to run needs to be in ./web/src folder

2. Run `docker compose up --build` to start 
