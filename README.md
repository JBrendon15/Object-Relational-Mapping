# Object-Relational-Mapping

## Description

For this project we learned how to create relationships between two tables of data in MySql databases. We learned how to establish many to many relationships, one to one relationships, and one to many relationships. We established a one to one relationship between our product table and our category table. We then established a many to many relationship between our product table and tag table. We properly defined the relationship in our models/index.js file so that we can receive the data in our routes. We also learned how to include information from other tables into the tables that our routes give. For example we can include the products' information that is associated with the id of the tag we run our query. 

## Installation
  
Right click the 'package.json' file and click 'Open in Integrated Terminal' then type the following in your terminal to install the neccessary packages:
```
npm i
```
Right click 'schema.sql' file and click 'Open in Integrated Terminal' then type the following in the terminal to turn on mysql server:
```
mysql -u root -p
```
Enter your MySql password when prompted then type the following in the terminal to create the database on MySql server:
```
source schema.sql
```
Right click on 'server.js' file and click 'Open in Integrated Terminal' and then type the following to seed data into your new database:
```
npm run seed
```
Go into the server.js file and change line 18, "password:" to your MySql password in a string.

## Usage
Right click the 'server.js' file and click 'Open in integrated terminal
```
npm start
```
[Tutorial Video](https://www.awesomescreenshot.com/video/11566956?key=ed5b20276c011f3b58a9a6c418a6c1d2)