# Docker LAMP configuration

*(Linux, Apache, PHP, MySQL/MariaDb, PhpMyAdmin)*


## How to use

1.Build Docker images based on the configuration defined in the docker-compose.yml

    make build (docker-compose build) 


2.Start containers and run composition for all services defined in the docker-compose.yml

     make up (docker-compose up)


## How to connect to servers

| PHP    |         MySql         |               PhpMyAdmin |
|--------|:---------------------:|-------------------------:|
| http://localhost:80 | http://localhost:3306 |    http://localhost:8080 |


##  Database config

| DATABASE      |        USER        | PASSWORD |
|---------------|:------------------:|---------:|
| test_database |     test_user      | test_pwd |


## Links

* [Docker](https://developer.fedoraproject.org/tools/docker/about.html) how to install Docker
* [Docker Compose](https://developer.fedoraproject.org/tools/docker/compose.html) how to install docker-compose
* [WIKI page](https://en.wikipedia.org/wiki/LAMP_software_bundle) about LAMP
* [PhpMyAdmin](https://en.wikipedia.org/wiki/PhpMyAdmin) about PhpMyAdmin

