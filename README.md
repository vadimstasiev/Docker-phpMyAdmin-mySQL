# Docker phpMyAdmin with mySQL

To start:
```
docker-compose up --build
```
To stop and remove.
```
docker-compose down
```
To remove all containers:
```
docker rm $(docker ps -aq) -f
```
To remove all images
```
docker rmi $(docker images -a -q) -f
```

## phpMyAdmin on http://localhost:8000/
