## Spring and Spring Boot

* Spring and Spring Boot are both Java frameworks.
* Framework --> Toolkit that helps developers build and structure the code in an efficient and scalable way.
* Spring is powerful, but needs a lot of configurations. Developers need to manually configure the various components of the framework to get the application to work.
* Spring Boot is an opinionated version of Spring. It comes with pre-configured settings and dependencies, and also has an embedded web server that eases the creation and deployment of web apps.


## Spring's Inversion of Control (IoC) Container

* Spring Boot uses Spring Core's IoC container.
* Spring Boot allows us to configure how and when dependencies are provided to our application at runtime.
* IoC is often called Dependency Injection (DI), though it is not strictly correct. One way of achieving IoC is through DI and accompanying frameworks. Dependencies are injected into the app at runtime. Spring community uses the terms IoC and DI interchangeably.


## Spring Initializr

* This is the recommended way to create a new Spring Boot app.
* Specify the project details and dependencies in it, and generate the initial version of the app.


## API Contracts

* How should consumers interact with the API given by the providers? What data must consumers send (if needed) and what data should the API return? What should the API communicate if something goes wrong?
* API contract is an agreed upon API behaviour in code and documentation.
* Eg: Consumer Driven Contracts, Provider Driven Contracts, etc.
* API contract is a formal agreement between the software provider and a consumer that abstractly communicates how to interact with each other.
