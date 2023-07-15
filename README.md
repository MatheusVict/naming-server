[![Continuos Integration with github](https://github.com/MatheusVict/naming-server/actions/workflows/docker-image.yml/badge.svg)](https://github.com/MatheusVict/naming-server/actions/workflows/docker-image.yml)

# Eureka server for microservices

### microservices required:

- [api-gateway](https://github.com/MatheusVict/Erudio-API-Gateway)
- [cambio-service](https://github.com/MatheusVict/cambio-service)
- [book-service](https://github.com/MatheusVict/book-service)

# Getting start

## Localhost with applications:

#### To start using applications on localhost, you should run in this order

- 1 [naming-server](https://github.com/MatheusVict/naming-server)
- 2 [api-gateway](https://github.com/MatheusVict/Erudio-API-Gateway)
- 3 [cambio-service](https://github.com/MatheusVict/cambio-service) ```you should configure data base on: application.yml``` 
- 4 [book-service](https://github.com/MatheusVict/book-service) ```you should configure data base on: application.yml``` 

## Localhost with docker

#### if you want to start all application with one commando, you can use docker-compose on project root:

```
docker compose up -d
```

# Routes:

#### you can open on [localhost](htpp://localhost:8761) and you will see the Eureka Netflix server
