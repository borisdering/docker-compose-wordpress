# Simple Docker Compose File For Wordpress
## Install Docker Compose 
```
sudo curl -L "https://github.com/docker/compose/releases/download/1.29.2/docker-compose-$(uname -s)-$(uname -m)" -o /usr/local/bin/docker-compose
sudo chmod +x /usr/local/bin/docker-compose
```

## Run Wordpress
Run docker-compose by 
```
docker-compose up -d 
```
Shutdown the instance 
```
docker-compose down 
```
Remove all containers 
```
docker-compose rm 
```
Log into http://localhost:8000