## Install Postgres on Docker

### Create a folder to store Postgres instance

```
mkdir postgres-docker
cd postgres-docker
```

### Copy docker-compose.yml file

### Execute docker instance

```docker
docker-compose up -d
```

### Connect from pgadmin

http://localhost:5050/

### Get Container IP Address to connect

```docker
docker ps
docker inspect <CONTAINER_ID>
```
