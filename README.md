# postgres-docker
Docker instructions for PostgreSQL container

docker pull postgres

WIN10

docker run --rm --name postgres-cnt -e POSTGRES_PASSWORD=docker -it -p 5432:5432 -v postgres:/var/lib/postgresql/data postgres


docker run --rm --name postgres-cnt -e POSTGRES_PASSWORD=docker -d -p 5432:5432 -v $HOME/Apps/docker/volumes/postgres:/var/lib/postgresql/data postgres


https://hackernoon.com/dont-install-postgres-docker-pull-postgres-bee20e200198
