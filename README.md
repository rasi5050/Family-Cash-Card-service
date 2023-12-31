# Family-Cash-Card-service
This is a hobby project(5) to learn Java-Spring Boot and RESTful-API's by creating `CashCard service for Family Cash Cards`; an app for families to manage allowances in the form of digital debit cards. 
I built fully functional, robust, and secure REST API using Spring Boot by applying test driven development methodology
based on [Spring academy course track](https://spring.academy/courses/building-a-rest-api-with-spring-boot)


## Whats used?
Java + Spring Boot

## Objectives
Implement RESTful methods;  GET, PUT, PATCH, and POST and corresponding HTTP response status codes.
Leverage Spring Boot features like Inversion of Control container, annotations, and auto-configuration.
Build API using a layered architecture, ie. Spring Security -->  Spring Web --> Spring Data
Use Red, Green, Refactor process to implement Test driven development Methodology

## How to run the program?

`$ git clone https://github.com/rasi5050/Family-Cash-Card-service`

`$ cd Family-Cash-Card-service`

`$ ./gradlew build`

`$ ./gradlew test`

## Endpoints
### GET
/cashcards/{id}

### POST
/cashcards/{id}

### PUT
/{requestedId}

### GET
/{id}

These endpoints are defined in `src/main/java/example/cashcard/CashCardController.java`
and since test driven methodology is used, all the tests to the requeststests are defined in `src/test/java/example/cashcard/CashCardApplicationTests.java`

## Screenshots
<img width="1512" alt="Screenshot 2023-06-29 at 11 15 52" src="https://github.com/rasi5050/Family-Cash-Card-service/assets/12760472/7cb5baff-7134-4662-8b9e-9ec8d319178a">


--

Happy learning!
Happy to connect on [Linkedin](https://www.linkedin.com/in/rasi5050/)


