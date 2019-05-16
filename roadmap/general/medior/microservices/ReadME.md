# Micro services



##  Developing Microservices - Chris Richardson 

Algemeen :

Enterprises need to deliver better software faster. It's no longer sufficient to release quarterly or even monthly. Instead, organizations must use methods such as DevOps to frequently deploy changes into production, perhaps as often as multiple times per day. However, one obstacle to DevOps-style development is that organizations are often mired in monolithic hell. Key business applications are large, complex, unwieldy monoliths, so it's impossible to rapidly and safely deploy changes. The solution is to adopt the microservice architecture?an architectural style that has the testability and deployability necessary for DevOps.

Through a combination of lectures, discussions, and kata exercises, Chris Richardson walks you through using the microservice architecture to develop your applications. You'll learn how to deal with some of the key obstacles you'll face, including distributed data management, and discover strategies for refactoring a monolith to a microservice architecture.
Doel :

By the end of this two-day training course, you'll understand:
The essential characteristics of the microservice architecture, its benefits and drawbacks, and when to use it
Distributed data management patterns
Effective microservice testing strategies
Deployment options for microservices
Strategies for refactoring a monolithic application to a microservice architecture
And you'll be able to:
Architect an application as a set of microservices
Use sagas to maintain data consistency
Implement queries that span services
Test microservices
Refactor a monolith to services
Doelgroep :

Software Developers interested in developing microservices
Onderwerpen :


- DAY ONE:
- Overview of the microservice architecture
   - The microservice architecture as an architectural style
   - Benefits and drawbacks of microservices
   - The microservice pattern language

- Decomposition
   - Overview of decomposition
   - Decompose by business capabilities
   - Decompose by bounded context
   - Service design guidelines

- Maintaining data consistency
   - Overview
   - Maintaining consistency using sagas
   - Coordinating sagas
   - Countermeasures for data anomalies

- Querying
   - Overview
   - Using the API composition pattern
   - Using the CQRS pattern

- DAY TWO:
- Inter-process communication
   - Overview of inter-service and external communication
   - Using an API Gateway
   - Service discovery

- Testing strategies
   - Introduction to the testing pyramid
   - Writing consumer-driven contract tests
   - Developing component tests
   - Developing end to end tests

- Overview of deployment patterns
   - Multiple services per host
   - Service per VM
   - Service per container
   - Serverless deployment

- Refactoring
   - Incrementally refactoring a monolith into microservices
   - Strategy
- 1: stop digging
   - Strategy
- 2: split front-end & backend
   - Strategy
- 3: extract services
