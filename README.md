# 🎬 Cinema Service 🎬 
___
This is a simple app for a cinema service, which utilizes Spring and Hibernate technologies. Supports user registration, operating with cinema halls, movies, movie sessions, adding tickets to shopping cart and completing order. 

## 📽 Features
* User registration, login and log out
* Adding and deleting cinema halls, movies as administrator
* Creating and adding movie sessions as administrator
* Finding available movie sessions by date and time
* Creating shopping cart for a user
* adding tickets to the cart and completing the order
---
## 📽 Project architecture
The app is built using a 3-layer structure. The layers are:
* The DAO layer for DB connection
* The Service layer for the main business logic calculation
* The Controller level to send requests and handle responses
---
## 📽 Technologies stack
* Java 11
* Spring, Spring MVC, Spring Security
* Hibernate
* Maven
* TomCat
* MySQL
---
## 📽 Instructions
* Edit db.properties, replacing default values with your DB parameters
* Configure TomCat (better use vers. 9.0.50)
* Start TomCat
* On a login page log in with username 'admin' and password 'admin123'. You can change the admin credentials in DataInitializer class, inject() method
* Perform CRUD operations using Postman or other similar service
