This project involves various SQL tasks aimed at deepening your understanding of MySQL and relational databases. By completing the tasks, you will gain proficiency in managing MySQL users, granting privileges, defining primary keys and foreign keys, working with constraints, retrieving data from multiple tables using joins and unions, and understanding subqueries.

Learning Objectives
Upon completing this project, you will be able to explain the following concepts without external assistance:

General:

Creating a new MySQL user.
Managing privileges for a user to a database or table.
Understanding what a PRIMARY KEY is.
Understanding what a FOREIGN KEY is.
Using NOT NULL and UNIQUE constraints.
Retrieving data from multiple tables in a single query.
Working with subqueries.
Utilizing JOIN and UNION operations.
Requirements
General:

Allowed editors: vi, vim, emacs
All files must be executable on Ubuntu 20.04 LTS using MySQL 8.0 (version 8.0.25)
All files should end with a new line.
All SQL queries should have a comment just before them describing the task.
All files should start with a comment describing the task.
All SQL keywords should be in uppercase (e.g., SELECT, WHERE).
A README.md file at the root of the project folder is mandatory.
The length of your files will be tested using the wc command.
Installation and Setup
To get started with this project, you will need to have MySQL 8.0 installed on an Ubuntu 20.04 LTS system. If you don't have MySQL installed, you can do so using the following commands:

bash
Copy code
$ sudo apt update
$ sudo apt install mysql-server
Verify the installation:

bash
Copy code
$ mysql --version
mysql  Ver 8.0.25-0ubuntu0.20.04.1 for Linux on x86_64 ((Ubuntu))
To connect to your MySQL server, use the following command:

bash
Copy code
$ sudo mysql
Once connected, you can perform your SQL queries and manage the database. Exit the MySQL monitor with the quit command.

For testing in a container environment, you can use "container-on-demand" to run MySQL. In the container, credentials are typically root for both the username and password.

Importing a SQL Dump
To import a SQL dump into your MySQL database, follow these steps:

Create a new database (replace hbtn_0d_tvshows with your desired database name):
bash
Copy code
$ echo "CREATE DATABASE hbtn_0d_tvshows;" | mysql -uroot -p
Download and import the SQL dump into the newly created database:
bash
Copy code
$ curl "https://s3.amazonaws.com/intranet-projects-files/holbertonschool-higher-level_programming+/274/hbtn_0d_tvshows.sql" -s | mysql -uroot -p hbtn_0d_tvshows
Verify the data has been imported:
bash
Copy code
$ echo "SELECT * FROM tv_genres" | mysql -uroot -p hbtn_0d_tvshows
Additional Resources
To help you with this project, here are some useful resources you can read or watch:

How To Create a New User and Grant Permissions in MySQL
How To Use MySQL GRANT Statement To Grant Privileges To a User
MySQL Constraints
SQL Technique: Subqueries
Basic Query Operation: The JOIN
SQL Technique: Multiple Joins and the DISTINCT Keyword
SQL Technique: Join Types
SQL Technique: UNION and MINUS
MySQL Cheat Sheet
The Seven Types of SQL Joins
MySQL Tutorial
SQL Style Guide
MySQL 8.0 SQL Statement Syntax
Project Tasks
This project involves completing various SQL tasks to meet the learning objectives mentioned above. You should write SQL scripts to accomplish the tasks provided in the project instructions.

Note: Remember that copying and pasting someone else's work is not allowed, and plagiarism will result in removal from the program.

Good luck with your SQL project! If you have any questions or need further assistance, feel free to reach out.






Regenerate

