![GitHub Logo](https://s3.ap-south-1.amazonaws.com/greyatom-social/GreyAtom-logo.png)

# RDBMS

RDBMS stands for Relational Database Management System. RDBMS is the basis for SQL, and for all modern database systems like MS SQL Server, IBM DB2, Oracle, MySQL, and Microsoft Access.

A Relational database management system (RDBMS) is a database management system (DBMS) that is based on the relational model as introduced by E. F. Codd.

RDBMS used for data where the data is structured, i.e. you can represent the data in a tabular format without repeating the data values. So RDBMS is good in handling structured data.
To handle RDBMS, we have a specific language called the Structured Query Language (SQL). SQL is common to all the below mentioned databases. Some of the features and formats vary is different databases but learning SQL in general can make it very easy to pick up any Relational Database System in no time.
Some of the most common examples of RDBMS are:


#### *__Tables__*
The data in an RDBMS is stored in database objects which are called as **tables**. This table is basically a collection of related data entries and it consists of numerous columns and rows.
Remember, a table is the most common and simplest form of data storage in a relational database. A column is a vertical entity in a table that contains all information associated with a specific field in a table.


#### *__Field__*
Every table is broken up into smaller entities called fields.
A field is a column in a table that is designed to maintain specific information about every record in the table.


#### *__Row__*
A record is also called as a row of data is each individual entry that exists in a table. A record is a horizontal entity in a table.


#### *__NULL value__*
A NULL value in a table is a value in a field that appears to be blank, which means a field with a NULL value is a field with no value.
It is very important to understand that a NULL value is different than a zero value or a field that contains spaces. A field with a NULL value is the one that has been left blank during a record creation.


#### *__Data Integrity__*
The following categories of data integrity exist with each RDBMS −
* **Entity Integrity** − There are no duplicate rows in a table.
* **Domain Integrity** − Enforces valid entries for a given column by restricting the type, the format, or the range of values.
* **Referential integrity** − Rows cannot be deleted, which are used by other records.
* **User-Defined Integrity** − Enforces some specific business rules that do not fall into entity, domain or referential integrity.

#### ***Constraints***
* **NOT NULL Constraint** − Ensures that a column cannot have a NULL value.
* **DEFAULT Constraint** − Provides a default value for a column when none is specified.
* **UNIQUE Constraint** − Ensures that all the values in a column are different.
* **PRIMARY Key** − Uniquely identifies each row/record in a database table.
* **FOREIGN Key** − Uniquely identifies a row/record in any another database table.
* **CHECK Constraint** − The CHECK constraint ensures that all values in a column satisfy certain conditions.
* **INDEX** − Used to create and retrieve data from the database very quickly.

