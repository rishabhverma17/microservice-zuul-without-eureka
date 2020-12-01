# Spring Boot Microservice with Gateway/Reverse proxy using Zuul
This service can be used to create microservice architecture with Gateway/Reverse Proxy using Zuul without using Eureka.

### Actual Microservice BaseUrl
- http://localhost:8181/catalog/
- http://localhost:8182/movies/
- http://localhost:8183/ratingsdata/


### Zuul Routes Path
- http://localhost:8762/actuator/routes

### Aliased Path to service
- http://localhost:8762/yourService/catalog/1
