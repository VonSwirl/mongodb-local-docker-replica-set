# mongodb-replica-set

MongoDb Replica Set with Docker Compose

## Install

- Clone this repository
- Go to directory of docker-compose.yml file
- Run command from Terminal

`docker-compose up`

## Connect

- from same network in Docker host

`mongodb://mongo1,mongo2,mongo3`

- from outside of Docker Host
- add `127.0.0.1 mongo1 mongo2 mongo3` to your etc/host file!

`mongodb://localhost:27017,localhost:27018,localhost:27019`
