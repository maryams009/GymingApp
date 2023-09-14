��#   G y m i n g A p p 


## Project Overview

This is the README file for the Q-Gym project. It provides an overview of the project, including setup instructions and important configuration details.

## Database Configuration

To configure the database for this project, you can use the following settings in your `application.properties` or `application.yml` file:

```properties
spring.datasource.url=jdbc:mysql://localhost:3306/gym
spring.datasource.username=root
spring.datasource.password=2131
spring.datasource.driver-class-name=com.mysql.cj.jdbc.Driver
spring.jpa.properties.hibernate.dialect=org.hibernate.dialect.MySQL8Dialect
spring.jpa.hibernate.ddl-auto=update
spring.jpa.show-sql=true
 
 
