# Repository for ElasticSearch

Repository of docker-compose manifests to run different versions of ElasticSearch and Kibana using Docker. 

## Software Requirements

docker compose file version: 3

## Run

build and start

```
docker-compose -f docker-compose-7.0.0.yml up --build
```

stop and remove

```
docker-compose -f docker-compose-7.0.0.yml down
```