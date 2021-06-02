# FlyAwayAppFranco
Java Hibernate Project

FlyAway

Steps to use
------------------------
1. Open in Eclipse IDE with Tomcat and Mysql
2. Create new database called "flyawaydb"
2. Load in table and data with information from db with setUpDB.sql file
3. Right Click Project Name and Run on Server
4. Go to http://localhost:8080/FlyAwayAppFranco/index.html

User Stories
----------------------
As a user,
I want to be able to search for available flights (Date of travel, source, destination, number of seats available, price),
Then I fill the index.html given form
So that I can select a flight

As a user,
I want to see the avialable flights with their source destination airline and prices,
So that I can choose the best option for me
Then I fill the form on the sell-all-flights given path And I submit the flight registration

As a user,
I want a confirmation page with proof of payment and details of my booking,
So that I can know the details on the day of my flight

As an admin,
I want to be able to change my password after login,
So that I can keep my account secure

As an admin,
I want to view a master list of places for source and destination,
So that I know all of the places my booking portal offers

As an admin,
I want a view a list of airlines,
So that I know what airlines are available to my customers

As an admin,
I want to view a list of all flights where each flight has a source, destination, airline, ticket price, and number of seats empty,
So that I know which flights to advertise more heavily



Tables for FlyAwayDB
------------
Airline (a_id, airline)

Flight (f_id, number_of_seats, price, source, destination,date_of_departure, date_of_arrival, a_id)

Person (per_id, first_name, last_name, email, birthday, timebooked)

personflight (per_id, f_id)

Payment (pay_id, card_number, expiration_month, expiration_year, security_code, card_fname, card_lname, per_id)

Admin (admin_id, first_name, last_name, email, password)

Concepts
------------------
Servlets
Session Management
Hibernate CRUD operations
SQL/DDL Queries
Many to Many, Many to One Relationships
Table Joins, Filters, Subqueries
Transaction Control
Maven

Sprint 1 user section
-Create DB
-Create User Form Index Page and List all Given flights
-Filter By User Form on Index.html 

Sprint 2 user section
-Show All the Details Of The Flight Source Destination prices
-Create Entities and Relationship
-Refactor DB Depending on Changes by Hibernate

Sprint 3 admin section
Show Airlines, Source Destination and Flights 


## Images
![Alt text](screen_1.png?raw=true "Title")
## Second Menu
![Alt text](screen_2.png?raw=true "Title")
## Deleting Option
![Alt text](screen_3.png?raw=true "Title")
## Searching Option
![Alt text](screen_4.png?raw=true "Title")

Please make sure to update tests as appropriate.
## Note 
Tested on macOS jdk 16
## License
[MIT](https://choosealicense.com/licenses/mit/)
