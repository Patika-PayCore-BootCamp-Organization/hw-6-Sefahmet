**1** – What is the difference between manual testing and automated testing?

Manuel testing process is realized with personal effort, and sometimes it could be a mistake. But automated testing is created with the project and it helps the test code easily.

**2** – What does Assert class?

When we have test scenario on the project, assert classes are shows the result of the test. Assert class uses for automated testing.

**3** - How can be tested “private” methods?

Actually, we don’t need the test private methods. When we test the public methods, which are called private methods, it is enough for testing.

**4** – What is Monolithic Architecture?

Monolithic Architecture means composed all in one piece in software. The monolithic Architecture software should be loosely coupled, it can test itself, and hierarchy of project must be in a suitable format.

**5**- What are the best practices to write a Unit Test Case?

It is the “expected, actually” system. When we give input to method, the returns of method are actually and we compare with our expected value. If the results are equal, we get return with assert class True or False.

**6** - Why does JUnit only report the first failure in a single test?

Reporting multiple failures in a single test is generally a sign that the test does too much and it is too big a unit test. JUnit is designed to work best with a number of small tests. It executes each test within a separate instance of the test class. It reports failure on each test.

**7** - What are the benefits and drawbacks of Microservices?

\- Microservices have complex architecture so it is hard for testing and monitoring.

\- The communication of microservices causes low performance.

\- Hard network maintenance.

\- Some security problem


**8** - What is the role of actuator in spring boot?

Actuator is mainly used to expose operational information about the running application — health, metrics, info, dump, env, etc.

**9** - What are the challenges that one has to face while using Microservices?

Design: While the project was growing, the microservices will be more complex.

Security: Microservices use multi-cloud environments, so the security bug could be realized.

Testing: Testing is so complex for microservices-based applications.

**10** - How independent microservices communicate with each other?

Microservices can communicate with each other through:

HTTP for traditional Request-Response.

WebSocket for streaming.

Brokers or Server Programs running Advanced Routing Algorithms.

For message brokers, RabbitMQ, Nats, Kafka, etc., can be used, each built for a particular message semantic. Another way is to use Backend As A Service like Space Cloud, which automates the entire backend.

**11** - What do you mean by Domain driven design?

Domain-driven design is the idea of solving problems of the organization through code. The business goal is important to the business users, with a clear interface and functions. This way, the microservice can run independently from other microservices.

**12** – What is container in Microservices?

A container is a bundling of an application and all its dependencies as a package, that allows it to be deployed easily and consistently regardless of environment. These dependencies include binaries, libraries, and configuration files needed to run the app.

**13** - What are the main components of Microservices architecture?

Containers, Service Mesh, Service Discovery, API Gateway.

**14** - How does a Microservice architecture work?

A microservice attempts to address a single concern, such as a data search, logging function, or web service function. This approach increases flexibility—for example, updating the code of a single function without having to refactor or even redeploy the rest of the microservices architecture.
