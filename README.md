# Relational Database for Airport Management System
**This project designs and implements a relational database to meet specific business requirements. The database is for an airport management system that controls the daily operations that provide services to airlines and passengers. The SQL files for this are available in the SQL files folder.**  

## Entity Relationship Diagram (ERD)
Based on the business rules, entities and attributes were identified. The relationships, connectivites and cardinalities between the entities were also mapped out. This has been modelled in the Entity Relationship Diagram (ERD) below. 
![Entity Relationship Diagram of database for airport management system](https://github.com/ShriyaSami/Relational-Database/blob/7eef7c73870f61ec6795b156f1f2f0ffae718941/ERD.png)

All the data was normalised to third normal form (3NF) to prevent data duplication, data inconsistency and data redundancy.  

## Implementation (with SQL)  
To implement the database, using SQL, the following steps were taken:
1.	Creating a table for each entity. 
This also involved assigning primary keys, data types and constraints for each column. 
2.	Populating the tables with data. 
This involved inserting correct and incorrect data to ensure the constraints were performing as expected. 
3.	Implementing query optimisation techniques.
For this, the following optimisation techniques were used: indexing, hash partitioning and range partitioning. 
4.	Ensuring concurrency control. 
This was done to simulate the real-world environment where the database would be implemented; it ensured that the database would be able to handle concurrent transactions.

To demonstrate successful implementation, the database was queried to return meaningful data. A variety of SQL queries were used, including joins, order by, aggregate functions, distinct and nested queries.
