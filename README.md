# spring-boot-logging
spring-boot-logging
### Build and run

#### Configurations

Open the `application.properties` file and set your own configurations.

#### Prerequisites

- Java 8
- Maven > 3.0

#### Using the terminal

Go on the project's root folder, then type:

    $ mvn spring-boot:run

#### From Eclipse (Spring Tool Suite)

Import as *Existing Maven Project* and run it as *Spring Boot App*.

### Usage

- Launch the application and go on http://localhost:8080/
- Take a look to console output: you should see some log from 
  `com.boot.application.app.controllers.HomeController`
- Optional: if you setted a log file in the `application.properties` open such file to see the log

# log4j Features
- It is thread-safe.

- It is optimized for speed.

- It is based on a named logger hierarchy.

- It supports multiple output appenders per logger.

- It supports internationalization.

- It is not restricted to a predefined set of facilities.

- Logging behavior can be set at runtime using a configuration file.

- It is designed to handle Java Exceptions from the start.

- It uses multiple levels, namely ALL, TRACE, DEBUG, INFO, WARN, ERROR and FATAL.

- The format of the log output can be easily changed by extending the Layout class.

- The target of the log output as well as the writing strategy can be altered by implementations of the Appender interface.

- It is fail-stop. However, although it certainly strives to ensure delivery, log4j does not guarantee that each log statement will be delivered to its destination.
