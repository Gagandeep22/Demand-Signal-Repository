# Demand-Signal-Repository

## Contributors:
Raj Nandu  
Nilay Rane  
Nishit Maru

## About:  
This is a Web driven project, essentially an **Inventory Management System**, which provides options such as:  
* Data Entry
* Edit Data
* Delete Data
* Transfer Items between labs
* Generate Reports:

      1.General Report
      2.Transfer Report
      3.Deleted items report
      4.Summary report
      
* Update User details
* Rollback Data Entry, Delete and Transfer operations

---
### Types of Users:
There are two types of users who can use the system, Admin and the lab assistant or lab incharge.
The set of actions available to both the users is different. Admin can access all the above listed functions, Lab assistant or Lab incharge have access to generating reports for their respective labs and updating their credentials.

---
### Programming tools used:
1. For Frontend developement

      * HTML
      * CSS
      * Bootstrap

2. For Backend developement

      * PHP
      * MySQL

3. Javascript and Jquery has been used in certain areas for validation and control purposes.

4. Xampp / Wamp for running MySQL

---
### Instructions for use:
1. Download/clone the project and move it in *htdocs* folder of Xampp.
2. Import the database/SQL file in phpMyAdmin under the name dsr.
3. Index file is *Login.php*
4. Default credentials for Admin access:

      `Username: admin`
      
      `password: 123`

5. Default credentials for Lab assistant:

      `Username: labasst`
      
      `password: 123`
      
6. Default credentials for Lab incharge:

      `Username: labinch`
      
      `password: 123`
      
*Note: The connection details can be changed in the connection.php file*

---
### Documentation:
The Code will be documented as well as a document manual will be uploaded in a span of few days, since the project is stil under testing.

---
### Bugs:
Project is under testing by the College authority for finding out the bugs and breakdown points.
