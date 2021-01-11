# Simple ORM (Hibernate) feature

## This is a simple Hibernate feature using:
* Java 8
* Maven
* MySQL
* Hibernate
* JPA
* DAO

### This program implements 3 entities: Customer, Product, Order.
### Relationships One-to-Many, Many-to-One, Many-to-Many are used between entities.

### Methods have been implemented in DAO:

DAO methods|
------------|
 findById|
 findAll|
 save|
 update|
 delete|
 
 ### Hibernate configuration is done dynamically, XML did not provide login and password protection.
 ### Used environment variables to communicate with MySQL database.
 ### A small utility GetEnv was created to get the variables

<img src="https://github.com/VladGithu8/HibernateFeature/blob/screanshots/Screanshots/photo_2021-01-10_17-05-31.jpg" width="700">

### The main class contains data for checking the program

## Customers:
<img src="https://github.com/VladGithu8/HibernateFeature/blob/screanshots/Screanshots/photo_2021-01-10_17-05-43.jpg" width="700">

## Products:
<img src="https://github.com/VladGithu8/HibernateFeature/blob/screanshots/Screanshots/photo_2021-01-10_17-05-40.jpg" width="700">

## Orders:
<img src="https://github.com/VladGithu8/HibernateFeature/blob/screanshots/Screanshots/photo_2021-01-10_17-05-37.jpg" width="700">

## Hibernate creates tables, adds data and implements relationships in MySQL
<img src="https://github.com/VladGithu8/HibernateFeature/blob/screanshots/Screanshots/photo_2021-01-10_17-05-23.jpg" width="700">

<img src="https://github.com/VladGithu8/HibernateFeature/blob/screanshots/Screanshots/photo_2021-01-10_17-05-26.jpg" width="700">
<img src="https://github.com/VladGithu8/HibernateFeature/blob/screanshots/Screanshots/photo_2021-01-10_17-05-18.jpg" width="400">

## Protection against data duplication is also implemented!
<img src="https://github.com/VladGithu8/HibernateFeature/blob/screanshots/Screanshots/photo_2021-01-10_17-05-34.jpg" width="700">

## The database received all the data and correctly placed it in the tables
## We can see result in MySQL database:
<img src="https://github.com/VladGithu8/HibernateFeature/blob/screanshots/Screanshots/photo_2021-01-10_17-05-12.jpg" width="700">



