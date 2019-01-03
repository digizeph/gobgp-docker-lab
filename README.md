# gobgp-docker-lab

GoBGP docker lab.

## Usage

To start all the routers:
```
docker-compose up -d
```

To bash into any routers and do a list of neighbors (for example):
```bash
docker ps
# get the router's docker instance id as DOCKER_ID
docker exec -it DOCKER_ID bash
# then inside the docker instance
gobgp neighbor
```
