# Spring Boot CRUD Application

Simple web application with Springboot, Thymeleaf and Mysql database.

## Requirements

Edit the 'application.properties' file in 'src/main/resources' to connect a mysql database.

```properties
spring.datasource.url = jdbc:mysql://localhost:3306/database
spring.datasource.username = username
spring.datasource.password = password
```

Declare the Java version in the pom.xml file.
```xml
<properties>
    <java.version>14</java.version>
</properties>
```