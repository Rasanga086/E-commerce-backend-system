# Welcome, 23IT0474!

## Your Role
Database configuration using H2

## What You Did & How It Works
You configured the database and application settings.

- **application.properties**: This file contains the very important settings to connect the backend to the H2 database. It tells the Spring application where the database is, what username and password to use, and how to create the tables automatically.

Your file connects to the whole project. Without your configuration, none of the Repositories built by the other members would be able to save any data!

## Your Files
We have copied your specific files into the `my_files` folder right here so you can easily see them. The files you worked on are:

- `src/main/resources/application.properties`

These files belong to your part of the project. If you need to make changes, remember to do it in the main project folder, not just here!

## Your Code Explained

Below are the actual files you worked on, along with an explanation of what the code inside them does.

### application.properties
These are the application properties. They configure important settings like the database connection details, server port, and other Spring Boot behaviors.

```properties
spring.application.name=ecommerce
spring.datasource.url=jdbc:mysql://localhost:3306/ecommerce
spring.datasource.username=root
spring.datasource.password=0318
spring.jpa.hibernate.ddl-auto=update
spring.jpa.show-sql=true
server.port=8080
```

