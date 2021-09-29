# step to setup the project

Create a requirements list
create a Docker file
create a Docker Compose file
build a Docker image
run a Docker Compose file


# build the image

docker build --tag python-django .


# create a container for the given image

docker run --publish 8000:8000 python-django

# use docker compose to build and run the container

docker-compose build
docker-compose run --rm app django-admin startproject core .
docker-compose up