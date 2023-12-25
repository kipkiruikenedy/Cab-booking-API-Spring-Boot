# REST API for Online Cab Booking Application

* To Create an Application for Online Cab Booking 

* Customer should be able to view the list of available cabs.

* Customer should be able to book cab for desired location from a certain location. 

* Admin should be able to perform below operations:

      1. Cab Management 
      2. Driver Management
      3. Booking Management

## Tech Stack:

* Java
* Spring Framework
* Spring Boot
* Spring Data JPA
* Hibernate
* MySQL
* Lombok
* Swagger

## Modules:

  * Login Module
	* Admin Module
	* Customer Module
	* Driver Management Module
	* Cab Management Module
	* Booking Management Module

## Installation & Run

* Before running the API server, you should update the database config inside the [application.properties](https://github.com/Samrat-Sinha/Online-Cab-Booking-Application/blob/main/Online_Cab_Project/pom.xml) file. 
* Update the port number, username and password as per your local database config.

```
    server.port=1995

spring.datasource.url=jdbc:mysql://localhost:3306/online_cab
spring.datasource.driver-class-name=com.mysql.cj.jdbc.Driver
spring.datasource.username=root
spring.datasource.password=root

```

## Swagger Deployed link
http://localhost:1995/swagger-ui/index.html#/

### Sample API Response for User Login

`POST   localhost:1995/online_Cab_Booking_Application/login`

* Request Body

```
    {
        "email": "kenedy@gmail.com",
        "password": "kened123"
    }
    
  

 
