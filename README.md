# ANALYTICS API

## Install

- Install and run [Docker](https://www.docker.com/) *(this project use **docker-compose**)*.

- Download or clone this git repository in your local machine.

- Open terminal and change directory to root project.

- Execute `docker-compose build` to install **docker images**.

## Run develop environment

- Execute `docker-compose up -d develop` to init **docker container**.

> Use `docker-compose up -d --build develop` in case the docker files have been changed.

> The default command is `python manage.py runserver`.

## Stop

- Execute `docker-compose stop` to **stop** container.

*or*

- Execute `docker-compose down` to **stop** and **delete** container.

## Install with PIP

- Add your package in `~/requirements.txt` file.

- Execute `docker-compose up -d --build develop` to install packages with PIP.

> If docker container is running execute `docker-compose down` to stop and delete container.

## Execute commands

Execute `docker-compose exec develop bash` to attach the container terminal.

## Code scaffolding

#### startapp

Execute `django-admin startapp NAME` to create new app into project.

---

### Additional resources

- [Docker get started](https://www.docker.com/get-started)
- [Django REST Framework tutorial](https://medium.com/backticks-tildes/lets-build-an-api-with-django-rest-framework-32fcf40231e5)