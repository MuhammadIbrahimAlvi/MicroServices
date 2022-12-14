# MicroServices
This project is about MicroServices and it's best practices.
What is MicroServices and on what principle it's based on?
---
Microservices is an architecture design model with a specific bounded context, configuration, and dependencies. These result from the architectural principles of the domain-driven design and DevOps. Domain-driven design is the idea of solving problems of the organization through code.

The business goal is important to the business users, with a clear interface and functions. This way, the microservice can run independently from other microservices. Moreover, the team can also work on it independently, which is, in fact, the point of the microservice architecture.

<b> What is Domain Driven Design <b>
---
Eric Evans, introduced the concept in 2004, in his book Domain-Driven Design: Tackling Complexity in the Heart of Software. According to the book, it focuses on three principles:

* The primary focus of the project is the core domain and domain logic.

* Complex designs are based on models of the domain.

* Collaboration between technical and domain experts is crucial to creating an application model that will solve particular domain problems.

     <img width="697" alt="Screenshot 2022-08-15 at 3 40 58 PM" src="https://user-images.githubusercontent.com/65025980/184621471-9108ad1e-40a6-4090-8143-84676e603d0d.png">
 Advantages of Domain-Driven Design
 ---
Visit following link for more details:

Reference from : https://medium.com/microtica/the-concept-of-domain-driven-design-explained-3184c0fd7c3f
     
Writtern by : Sara Miteva 
     
https://saramiteva.medium.com/

Microservices are considered to be service oriented architecture. From outside a single microservice is considered to be black box.
     
Microservices embraces the concept of data hiding. This help in maintaining the services based on different domain and the changes in them doesn't effect the other service.
     
SOA vs MicroServices
---
SOA is a design pattern in which multiple services combine to perform a certain tasks through different availble endpoints. The SOA emphasizes on reusing the code for different problems. 

Key Concepts of MicroServices:
---
* Independent Deployability: This allow application to be loosely coupled and one application will be deployed without changing anything in the other service.

* Modeled around Business Domain: 
     
     <img width="492" alt="Screenshot 2022-08-15 at 5 24 34 PM" src="https://user-images.githubusercontent.com/65025980/184634575-2dbd53fb-ecb2-4a3e-99ea-d6047c8a47ac.png">
     
Separating the business model will allow to make things easier, the domain of every business will be different so making change in one business domain will not effect the other.

* Owning their own State: Every Microservice should have their own state like if one service want to access the data from the other service it will require permissions from other service to allow access to the data, also it will keep the Object Oriented encapsulation principle alive of data hiding principle.

Three C's of Microservices:
---


Monolithic:
---
<img width="485" alt="Screenshot 2022-08-15 at 7 40 57 PM" src="https://user-images.githubusercontent.com/65025980/184656629-76ad33ce-17ef-4733-b4b7-762772271df0.png">


     
