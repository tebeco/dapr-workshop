## Cloud Native Applications

Cloud has changed the way we develop our applications. Cloud provides benefits like - agility, availability, scalability, resiliency and many more. To make most out of these benefits, we need to choose correct architecture and processes for developing our applications. We need to develop applications in "Cloud Native" way. We need a cloud native development model

Cloud native applications uses containers, APIs, microservices and devops. Microservices architecture has lot of advantages as compared to traditional layered architecture also known as monolith architecture. 

 "Microservices applications are composed of small, independent services that communicate with each other using well-defined APIs"
 
 But developing microservices application is quite hard. Some challanges -
 
 * You need to design your application as set of independent services. Each of these service should model around the business domain.
 * You need to choose right technology stack for each service.
 * These services should have well defined interfaces. You need to keep these interface consistent so that changes in these services does not break other services which are using them
 * You need to handle distributed transaction across services
 * And many more ...
 
Each microservices application has some common set of challanges -

* Service to service invocation
* State management
* Secret managment
* Distrubuted tracing
* Pub-sub
* Actors
