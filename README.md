#Memento Cloud Config Server
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Build status](https://github.com/tzarsmango/memento-cloud-config/workflows/Publish%20master/badge.svg)](https://github.com/tzarsmango/memento-cloud-config/actions)


This service is a part of the [memento](https://github.com/users/tzarsmango/projects/1) project. This application uses 
a Spring Cloud Config Server instance to serve the configuration files in this [repository](https://github.com/tzarsmango/memento-cloud-config-repo)


### Prerequisites

- [Open JDK 11](https://openjdk.java.net/projects/jdk/11/)
- [Spring Boot](https://spring.io/projects/spring-boot)
- [Docker](https://www.docker.com)
- [Gradle](https://gradle.org)

### Building

The project uses [Gradle](https://gradle.org/).

To build project please execute the following:

```bash
./gradlew clean build
```

### Running locally
This project tastes best with its companion services. See [here](https://github.com/tzarsmango/memento-docker) for a 
convenient way of running `memento` application.