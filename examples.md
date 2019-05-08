# examples of docker-compose.yml possible

## mysql setup

```
demo-mysql:
  image: mysql:latest
  environment:
    - MYSQL_ROOT_PASSWORD=p4SSW0rd
    - MYSQL_DATABASE=demo
    - MYSQL_USER=dbuser
    - MYSQL_PASSWORD=dbp4ss
```

```
  movie-quote-database:
    image: mysql:8.0.14
    environment:
      - MYSQL_ROOT_PASSWORD=password
      - MYSQL_USER=dbuser
      - MYSQL_PASSWORD=dbpass
      - MYSQL_DATABASE=quotes
      - MYSQL_ONETIME_PASSWORD=true
 ```
 
 
 
 ```
 
 ```
