# Microservices

Microservices

https://www.youtube.com/watch?v=rv4LlmLmVWk

https://raw.githubusercontent.com/RodrigoMvs123/Microservices/main/README.md


https://github.com/RodrigoMvs123/Microservices/blame/main/README.md


Monolith 
All components are part of a single unit
in 1 code base
Everything is Developed, Deployed and Scaled as 1 unit
App must be written with 1 tech stack
Teams need to be careful to not affect each other's work
1 single artifact, so you must redeploy the entire application on each update

user-auth
shopping-cart
product-catalog
notifications
payment

Microservices Architecture 

Split application into smaller, independent services 
Service A, B, C, D.
Split based on Business Functionalities 

Products 
Shopping-Cart
User 
Checkout

Separation of Concerns 
1 Service for 1 specific job 
Self Contained and Independent 
Developed, Deployed,  and Scaled separately 

Each Microservice has its own version 
Communication via API Calls
Each service has it own API
Message Broker ( Asynchronous Communication ) 
Communication via messages 
Common distribution patterns: Publish/ Subscribe and Point-to-point messaging  
Communication Service Mesh ( Control Plane - Proxy / Service )

Each Microservice team can choose its own tech stack
Security 
Messaging
Orchestration 
Service Mash
Containers 
Monitoring 

Kubernetes 

GitLab
Monorepo
Polyrepo 



 
