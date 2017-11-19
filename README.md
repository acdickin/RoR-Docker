#RoR-Docker

##To build project with postgres DB
```
docker-compose run web rails new . --force --database=postgresql
```

##Create user
```
sudo chown -R $USER:$USER
```

##Build container
```
docker-compose build
```

## Run the container
```
docker-compose up
```

##Create Database
```
docker-compose run web rake db:create
```
