
# SQL Interview Questions  - Quiz


## Introduction

This quiz contains questions on topics you can expect to see in an interview pertaining to SQL and Relational Databases. Some of them are multiple choice, while some are short answer. For these short answer questions, double click on the Jupyter Notebook and type your answer below the line. 

## Question 1

What are the 4 main datatypes in SQLite3? Can we use other common types from other kinds of SQL?

Type your answer below this line:TEXT

INTEGER

REAL

BLOB

yes SQLite datatypes are flexible and allows one to work with the common SQL types without issues eg FLOAT can be used for REAL and CHAR for TEXT.

_______________________________________________________________________________________________________________________________





## Question 2

Explain the relationship between **Primary Keys** and **Foreign Keys**.

Type your answer below this line:
A primary key in one table is often used as a reference  in another table as a foreign key. At the same time the foreign key column in the referencing table must have the same datatype  as that of the primary key

_______________________________________________________________________________________________________________________________





## Question 3

Explain the different types of relationships entities can have in a SQL database. 

Type your answer below this line:
one- to - one  here one record in a table is associated  with one and only one record in anther table often used to split data into multiple tables 

one- to- many  here one record in a table is associated to multiple records in another table.

many- to - many multiple records in one table are associated with multiple records in another table, always represented by an intermediary table referred to as a bridge table 
_______________________________________________________________________________________________________________________________


## Question 4

Explain the various types of JOINs possible with SQL. 

Type your answer below this line:

left (outer) join - returns all rows from the left table and the matching rows from the right table  if there are no matching elements in the right table  then Null values are returned.

cross join - returns a product of rows from both tables resulting in all possible combinations

self join- used to join a table with itself useful when dealing with recursive data.

full(outer) join -returns all the rows when there is a match in either left or right table.

right outer join- returns all rows from the right row and matching rows from the left table.

inner join -returns only rows that have matching rows on both tables 
_______________________________________________________________________________________________________________________________



## Question 5

Explain the relationship between Aggregate functions and GROUP BY statements.

Type your answer below this line:

 After  defining the groups you can apply aggregate functions  to each group separately using the SELECT clause, which results in a summary of data  where you have one row per group and the aggregate functions provide values based on the data within each group
_______________________________________________________________________________________________________________________________



## Question 6

What role do Associative Entities play (JOIN Tables) in many-to-many JOINs?


Type your answer
Associative entities are used to break down  complex relationship into two one-to - many relationships making it easier to represent in a relational  databasebelow this line:

_______________________________________________________________________________________________________________________________



## Summary

In this lesson, we practiced answering open-ended interview questions for SQL and Relational Databases. 
