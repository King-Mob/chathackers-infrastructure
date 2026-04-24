# Chathackers Infrastructure

This is the project that creates a chathackers docker container on a matrix server that was set up using the matrix-ansible-docker-deploy playbook. It assumes that a chathackers domain (main branch uses chathackers.uk) is pointing at the IP of the matrix server.

## Usage Instructions

1. put new env variables in the .env
2. run `docker compose build --no-cache` to build the container
3. run `docker compose up -d` to start the container
4. run `docker ps` to see the container
5. run `docker exec -it chathackers_uk bash` to open the container