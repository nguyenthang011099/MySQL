## What is SQL
SQL stands for Structured Query Language.
It is used to query the database for certain information or to carry out certain tasks.
It is a hybrid language and consists of DQL (Data Query Language), DDL (Data Definition Language), DCL (Data Control Language) and DML(Data Manipulation Language).
## What is MySQL
MySQL is a database management system.
MySQL databases are relational.
MySQL software is Open Source.
The MySQL Database Server is very fast, reliable, scalable, and easy to use.
Official link to the latest free community version of MySQL: https://dev.mysql.com/downloads/installer/
Official website: https://dev.mysql.com/
## Query data
This section helps you learn how to query data from the MySQL database server. We will start with a simple SELECT statement that allows you to query data from a single table.

SELECT – show you how to use simple SELECT statement to query the data from a single table.
## Sorting data
ORDER BY – show you how to sort the result set using ORDER BY clause. The custom sort order with the FIELD function will be also covered. Sorting can be in ascending order (ASC - default sorting if nothing is mentioned) or in descending order (DESC).
## Filtering data
WHERE – learn how to use the WHERE clause to filter rows based on specified conditions.

AND – introduce you to the AND operator to combine Boolean expressions to form a complex condition for filtering data.

OR– introduce you to the OR operator and show you how to combine the OR operator with the AND operator to filter data.

IN – show you how to use the IN operator in the WHERE clause to determine if a value matches any value in a list or a subquery.

BETWEEN – show you how to query data based on a range using BETWEEN operator.

LIKE  – provide you with technique to query data based on a specific pattern.

LIMIT – use LIMIT to constrain the number of rows returned by SELECT statement
## Joining tables
Table & Column Aliases – introduce you to table and column aliases.

Joins  – give you an overview of joins supported in MySQL including inner join, left join, and right join.

INNER JOIN – query rows from a table that has matching rows in another table
.
LEFT JOIN – return all rows from the left table and matching rows from the right table or null if no matching rows found in the right table.

RIGHT JOIN – return all rows from the right table and matching rows from the left table or null if no matching rows found in the left table.

CROSS JOIN – make a Cartesian product of rows from multiple tables.
## Grouping data
GROUP BY – show you how to group rows into groups based on columns or expressions.

HAVING – filter the groups by a specific condition.
## Modifying data in MySQL
NSERT – use various forms of the INSERT statement to insert data into a table.

INSERT INTO SELECT – insert data into a table from the result set of a query.

INSERT IGNORE  – explain you the INSERT IGNORE statement that inserts rows into a table and ignore rows that cause errors.

UPDATE – learn how to use UPDATE statement and its options to update data in database tables.
Syntax: 
		UPDATE <table_name>
		SET <update_attribute_values>
		WHERE <condition>;

UPDATE JOIN – show you how to perform cross table update using UPDATE JOIN statement with INNER JOIN and LEFT JOIN.

DELETE – show you how to use the DELETE statement to delete rows from one or more tables.
Syntax to delete a tuple (row) from a table:
	DELETE FROM <table_name>
	WHERE <condition>;

ON DELETE CASCADE – learn how to use ON DELETE CASCADE referential action for a foreign key to delete data from a child table automatically when you delete data from a parent table.

DELETE JOIN – show you how to delete data from multiple tables.

REPLACE – learn how to insert or update data depends on whether data exists in the table or not.
## MySQL data types
NT – show you how to use integer data type.

DECIMAL – show you how to use DECIMAL data type to store exact values in decimal format.

BIT – introduce you BIT data type and how to store bit values in MySQL.

BOOLEAN – explain to you how MySQL handles Boolean values by using TINYINT(1) internally.

CHAR – guide to CHAR data type for storing the fixed-length string.

VARCHAR – give you the essential guide to VARCHAR data type.

TEXT – show you how to store text data using TEXT data type.

DATE – introduce you to the DATE data type and show you some date functions to handle the date data effectively.

TIME – walk you through the features of TIME data type and show you how to use some useful temporal functions to handle time data.

DATETIME – introduce you to the DATETIME data type and some useful functions to manipulate DATETIME values.

TIMESTAMP – introduce you to TIMESTAMP and its features called automatic initialization and automatic update that allows you to define auto-initialized and auto-updated columns for a table.

JSON – show you how to use JSON data type to store JSON documents.

ENUM – learn how to use ENUM data type correctly to store enumeration values.
