### Micro server application for a travel agency management with SpringBoot, Node js, MongoDB, MySQL, H2, SpringCloud, Eureka-Netflix and Zuul. 
     :star: :star: :star: :star: :star:
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

 #####  I. Create a SpringBoot project adding these 7 dependencies : 
           1.  Spring Boot Actuator
           2.  Spring Data JPA 
           3.  Rest Repositories 
           4.  Spring Web 
           5.  H2 Database
           6.  Eureka Discovery Client
           7.  Config Client

#####   II. Create you Entity file ( this is an example that you can follow ) : DON'T FORGET TO GENERATE THE ANNOTATIONS & YOUR GETTERS/SETTERS 

![entites](https://user-images.githubusercontent.com/57329406/138796308-3ba8d323-2ca8-435a-95ca-2a01e99c4abd.png) 

#####   III. Create your Repository INTERFACE ( this is an example that you can follow ) : DON'T FORGET TO GENERATE THE @Repository 

![Repos](https://user-images.githubusercontent.com/57329406/138797224-323af116-8cfc-4381-ab73-87eca8b04127.png)

#####   IV. Create your SERVICES CLASS TO WRITE YOUR CRUD ( this is an example of simple CRUD creation that you can follow ) : DON'T FORGET TO GENERATE THE @Service 

![crud](https://user-images.githubusercontent.com/57329406/138797929-abb56301-189f-4785-8ca0-3b3d9c5800fb.png)

#####   V. Create your RestApi Class to write your Mappings ( this is an example that you can follow ) : DON'T FORGET TO GENERATE THE ANNOTATIONS

![REST](https://user-images.githubusercontent.com/57329406/138798966-66edbc37-ac5c-420e-a8fc-d5d0b23d50cb.png)

#####   VI. Configure your application properties ( this is an example that you can follow ) : IGNORE 

![app prop](https://user-images.githubusercontent.com/57329406/138799659-c2752080-4c8f-4cba-9a7f-da16664944ba.png)

#####  &#8594; Once you finished these steps, Start your application, try your Rest APIs on Postman & then check your H2 Database to be sure that your first mission is accomplished :muscle:
