# DDSCLOUD V3 #

Aplikasi versi 3 dari ddscloud.id

### Host Packages Details ###
* Docker
* Docker-compose
* PHP
* MYSQL
* APACHE2

## #HOW TO USAGE# ##

#### DOCKER COMPOSE INSTALL ####

Linux
```bash
sudo curl -L https://github.com/docker/compose/releases/download/1.19.0/docker-compose-`uname -s`-`uname -m` -o /usr/local/bin/docker-compose
```

```bash
sudo chmod +x /usr/local/bin/docker-compose
```

```bash
$ docker-compose --version
```

#### RUN COMMAND ####

Running docker-compose
```bash
$ docker-compose up -d
```

#### STOP COMMAND ####

Stop all containers created with a docker-compose command:
```bash
$ docker-compose stop
```

#### REMOVE VOLUME ####
Remove all those stopped containers including volumes that were attached to them:
```bash
$ docker-compose rm -v
```
Clean dangling volumes:
```bash
$ docker volume prune
```