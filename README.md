# microservice-project
A Microservices project using Spring Boot, containing 3 microservices Shopping Service, Billing Service, Payment Service.<br/>
These services are registered as clients on Eureka Server. <br/>
A config Server which manages configurations for these 3 services from the repo - "https://github.com/GauravJaiswal017/spring-cloud-config-repo". <br/>
API Gateway with Spring Security(using Auth0) which allows only authorized request to these services.<br/>
Circuit Breaker is implemented through resilience4j.<br/>
