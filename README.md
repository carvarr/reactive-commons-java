![](https://github.com/reactive-commons/reactive-commons-java/workflows/reactive-commons-ci-cd/badge.svg)
[![Reactor RabbitMQ](https://maven-badges.herokuapp.com/maven-central/org.reactivecommons/async-commons-rabbit-starter/badge.svg)](https://mvnrepository.com/artifact/org.reactivecommons/async-commons-rabbit-starter)
# reactive-commons-java
The purpose of reactive-commons is to provide a set of abstractions and implementations over different patterns and practices that make the foundation of a reactive microservices architecture.

Docs: https://reactivecommons.org/reactive-commons-java/

Other projects: https://github.com/bancolombia

Sponsor by: https://medium.com/bancolombia-tech

Even though the main purpose is to provide such abstractions in a mostly generic way such abstractions would be of little use without a concrete implementation so we provide some implementations in a best effors maner that aim to be easy to change, personalize and extend.

The first approach to this work was to release a very simple abstractions and a corresponding implementation over asyncronous message driven communication between microservices build on top of project-reactor and spring boot.
