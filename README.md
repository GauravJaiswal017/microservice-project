# microservice-project
Microservice project containing 3 microservices Shopping Service, Billing Service, Payment Service./n
These services are registered as clients on Eureka Server. 
A config Server which manages configurations for these 3 services from the repo - "https://github.com/GauravJaiswal017/spring-cloud-config-repo". 
API Gateway with Spring Security(using Auth0) which allows only authorized request to these services. 
Circuit Breaker is implemented through resilience4j.
