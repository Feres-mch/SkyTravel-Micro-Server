## Micro server application for a travel agency management with SpringBoot, Node js, MongoDB, MySQL, H2, SpringCloud, Eureka-Netflix and Zuul.
----
### We Will make it together step by step : 

* MicroServices : 
    1. SpringBoot / H2 database 
    2. SpringBoot / MySQL database
    3. Node js - Express js / MongoDB 

* Deployement of the Microservices on Eureka-Netflix server. 
* Gateway configuration with Zuul. 
* Configuring the SpringCloud config server.
* Dockerizing the Microservices, Eureka-Netflix server, Zuul & server config.  


**** 

#### First of all, let's start with creating the SpringBoot/H2 microservice 

 * Create a SpringBoot project adding these 7 dependencies : 
           1.  Spring Boot Actuator*
           2.  Spring Data JPA *
           3.  Rest Repositories* 
           4.  Spring Web *
           5.  H2 Database*
           6.  Eureka Discovery Client*
           7.  Config Client

* Create you Entity file ( that is an example that you can follow ) : 

