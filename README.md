# Luke's Store

This was a school project I made for a Java class. It uses Swing and a MySQL database. 

![Lukes Sales Tracker](https://image.ibb.co/dBA8jo/lukes_store.png)

## Getting Started
This can be a complicated process. In summary, Netbeans IDE and a MySQL database will be needed.
Next, a user account, tables, and columns will need to be created. After the database can be added to Netbeans. 
After, the code will need to be updated to include the user credentials created. 

### Installing
Using Netbeans IDE, open this project after downloading. 

Install the MySQL Database on your local machine and add it to Netbeans. A Google search can provide helpful steps on how to do this.

In the MySQL database, create a user account and the following tables/columns:

Table 1:
* product

Columns: 
* ProductName 
* ProductCategory
* ProductPrice


Table 2: 
* customer 

Columns:
* CustomerFN
* CustomerLN
* CustomerAddress1
* CustomerAddress2
* CustomerCity
* CustomerState
* CustomerZip
* CustomerPhone

In the code, change the connection URL and credentials to your own in LukesStore.java:
```
String url1 = "jdbc:mysql://localhost:3306/*your_database_here";
String user = "username";
String password = "password";
```
Run the code.

NOTE: Make sure the MySQL database is connected. A Google search can provide many examples on how to test the connection. 

### Prerequisites

* MySQL Database
* Netbeans IDE

## Built With

* [Netbeans](https://netbeans.org/downloads/) - the IDE used

## Authors

* **Luke Yaegel**
