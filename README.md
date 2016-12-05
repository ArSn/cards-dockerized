# cards-dockerized

Dockerized version of [ArSn/cards](https://github.com/ArSn/cards) to be started easily with the help of [docker-compose](https://docs.docker.com/compose/).

Installation steps:

1. `git clone https://github.com/ArSn/cards-dockerized.git`
2. Adjust desired server hostname in `nginx/cards.kaz.cool.conf` file (or rename/create own file and adjust `Dockerfile` accordingly)
3. `docker-compose up -f docker-compose.yml`