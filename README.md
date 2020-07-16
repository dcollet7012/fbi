# FBI : Facility Bus Integration

# Initialize the Project

## Maven Project

   - group-id : org.dco.fbi
   - artifact-id: fbi


## Modules

- fbi-quality : Checkstyle/Formatter/SpotBugs and other element for quality
 - fbi-product : The product
      - fbi-core : The core
      - fbi-cloud: Fbi In cloud
          - fbi-cloud-config-server : The server for configuration
          - fbi-cloud-service-registery-server : Register and Discover service over cloud
      - fbi-model : The global model for FBI
      - fbi-repository : The repository for entities
      - fbi-api-registery-service : Service for API and Endpoint registration
      - fbi-message-broker : The message broker
      - fbi-message-maintener: Auto Recycling, Archiving and Purge of message
      - fbi-webapp : The rest service for back-end operation
      - fbi-ui : The front-end as user interface
      - fbi-webapp : The web app back end for service registration and broker

## Dependencies Framework

- Spring Boot 2
- Spring Data Jpa
- String Security
- Spring Web
- Spring Actuator
- Spring Cloud Config Server
- Spring Cloud Consul
- Jackson
- ActiveMQ
- CXF
- Swagger
- Postgresql


## Plugins Management

- Maven Spring Boot
- Maven CheckStyle
- Maven SpotBugs
- Maven Surefire
- Maven Jacoco
- Maven Sonar







