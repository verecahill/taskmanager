# TaskManager

### Local development setup

- JDK8
- MySQL 5.7+
- RabbitMQ 3.6+
- GraphicMagick 1.3+

### Database setup

- Create database `task_agile`

### Add dev properties file

- application-dev.properties` 

## Commands

- Use `mvn test` to run the tests of the back-end and the front-end
- Use `mvn spring-boot:run` to start the back-end
- Use `npm run serve` inside the `front-end` directory to start the front-end
- Use `mvn install` to build both the front-end and the back-end
- Use `java -jar target/app-0.0.1-SNAPSHOT.jar` to start the bundled application
