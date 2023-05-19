# Cinema-app

## Introduction

This is a web application called "Cinema App" that allows users to register in the system and have their own personal cart where they can add tickets for movie screenings, choose cinema halls, search for specific movie screenings by date and movie, and more. It enables users to authenticate themselves with a login and password after registration. Each user also has a role (USER/ADMIN). The admin has additional privileges while using this web application, including access to methods such as "findUserByEmail" and others. This application operates using the Spring Framework, Hibernate ORM Framework, Apache Tomcat, and MySQL database.

## Features

- User registration and authentication
- Personalized shopping cart
- Search functionality for movie screenings
- Role-based access control (USER/ADMIN)
- Functionality for managing Cinema Halls, users, movies, etc. (for ADMIN)
- The whole project works through a database

## Technologies

- Java
- JDBC
- Tomcat
- Spring Framework
- Hibernate ORM Framework
- MySql
- Maven

## Project Structure
- `src/main/java`: Contains the Java source code for the application
- `src/main/resources`: Contains configuration files and resources

## Getting Started

#### To run the application, the following prerequisites are needed:

- Java 17 or later
- Apache Tomcat 9 (version 9.0.73 is recommended)
- MySQL 8 or later

#### To install the application, follow these steps:

1. Clone the repository using the command git clone https://github.com/Ukrainets-Oleksii/cinema-app
2. Open the project in your preferred IDE and build the project
3. In the file `src/main/resources/db.properties` you need to replace 4 parameters, they should be initialized with your own data:
    ```
    db.driver=YOUR_DRIVER
    db.url=YOUR_URL
    db.user=YOUR_USERNAME
    db.password=YOUR_PASSWORD
    ```
   ##### Recommendation:
   -   If you already have a database, you can use it, but I recommend creating a new database using the functionalities provided in `src/main/resources/init_db.sql`
   #####

4. Deploy the WAR file in Tomcat
5. Start the application

## Best Practices

#### When working on this project, the following best practices were followed:

- Clear and concise naming conventions were used for variables, classes and methods
- Code was organized into meaningful packages
- Defensive programming techniques were used to prevent bugs and exceptions
- Code was kept simple and maintainable to reduce the likelihood of introducing bugs and improve future maintainability
