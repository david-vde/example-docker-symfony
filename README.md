## Commands

### Build and run docker containers

```
docker-compose up -d --build
```

### Connection to a docker container with bash

Existing containers in this project:
- php74-container
- mysql8-container
- nginx-container

```
docker exec -it <container_name> bash
```

### Check services

```
docker-compose ps
```
