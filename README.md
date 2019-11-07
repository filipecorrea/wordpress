# wp-docker

WordPress setup using Docker Compose.

## Prerequisites

- [Docker](https://www.docker.com)

## Build and run

Run `docker-compose up -d` from your project directory and open [localhost](http://localhost) in a web browser.

## Shutdown and cleanup

Run `docker-compose down` from your project directory to remove the containers and network, but preserve the local data.

Run `docker-compose down --volumes` from your project directory to remove the containers, network, and local data.
