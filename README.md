# spring-rest-api
Spring REST API Project

Demonstrates all 4 basic HTTP request types with Spring REST.

GET, POST, PUT and DELETE controller methods implemented.

There's also a @ControllerAdvice present to show how to take control of the response from your api on a higher-level.

Source Code for http://udemy.com/learn-spring-and-spring-boot-10x-productive-java-development/


Run :
mvn spring-boot:run

GET:
http://localhost:8080/api/products/297e31c37a784d6d017a785cb7600004

Post:
http://localhost:8080/api/products/
{
    "name": "null234",
    "description": "asdfa",
    "type": "n33ull",
    "category": "nuaaall"
}