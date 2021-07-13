# README

# Versions
```
ruby '2.7.2'
rails '6.0.4'
```

# Requirement
```
Docker
docker-compose
```

# Usage
``` bash
$ git clone git@github.com:H0R15H0/dockerized-rails-api.git YOUR_APP_NAME
$ cd YOUR_APP_NAME
$ docker-compose build
$ docker-compose run --rm app yarn install --check-files
$ docker-compose run --rm app rails db:create
$ docker-compose up
# open http://localhost:3000/
```

# Change remote repository
```
$ git remote set-url origin https://github.com/USERNAME/REPOSITORY.git
```
