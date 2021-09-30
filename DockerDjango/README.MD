# command to build the docker image 

docker build -t docker-django .

# command to create and launch a container

docker run --publish 8000:8000 docker-django