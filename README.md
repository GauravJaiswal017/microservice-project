# microservice-project
A Microservices project using Spring Boot, containing 3 microservices Shopping Service, Billing Service, Payment Service.<br/>
These services are registered as clients on Eureka Server. <br/>
A config Server which manages configurations for these 3 services from the repo - "https://github.com/GauravJaiswal017/spring-cloud-config-repo". <br/>
API Gateway with Spring Security(using Auth0) which allows only authorized request to these services.<br/>
Circuit Breaker is implemented through resilience4j.<br/>

Flow Diagram of my project-
![Screenshot 2025-01-20 160627](https://github.com/user-attachments/assets/cb9446ac-96d4-4ec0-b309-6a578edd79cc)
