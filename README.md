# docker

## Run with command as follow:
```
docker run --name postgres12 -p 5432:5432 -e POSTGRES_USER=root POSTGRES_PASSWORD=123456 -d postgres:12-alpine
```
-p as a brige port expose to the local PC.

## Run the container
```
 docker exec -it postgres12 psql -U root
```
-it stands for interact mode

