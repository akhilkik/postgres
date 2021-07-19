![image](https://user-images.githubusercontent.com/85165326/126124980-f052ff49-10b1-4bb0-b3d0-ab182dad4240.png)
# Postgres :

-  Free and open-source relational database management system (RDBMS) emphasizing extensibility and SQL compliance.
- Originally named POSTGRES, referring to its origins as a successor to the Ingres database developed at the University of California, Berkeley  In 1996.

 ## Key Difference :
 
 - PostgreSQL is an Object Relational Database Management System (ORDBMS) whereas MySQL is a community driven DBMS system.
 - PostgreSQL support modern applications feature like JSON, XML etc. while MySQL only supports JSON.
 - Comparing PostgreSQL vs MySQL performance, PostgreSQL performs well when executing complex queries whereas MySQL performs well in OLAP & OLTP systems.
 - PostgreSQL is complete ACID compliant while MySQL is only ACID compliant when used with InnoDB and NDB.
 - PostgreSQL supports Materialized Views whereas MySQL doesn’t supports Materialized Views.

![image](https://user-images.githubusercontent.com/85165326/126125408-b4722f1a-b655-4b3d-aa16-cb82b19cdc65.png)
![image](https://user-images.githubusercontent.com/85165326/126125661-8832b1fd-87e1-4a24-8289-19ae16efd860.png)
![image](https://user-images.githubusercontent.com/85165326/126125757-9e41cd1a-7f02-4ede-92e3-0342647ff391.png)

## Common Table Expressions (CTE) :

- Common Table Expressions are temporary in the sense that they only exist during the execution of the query.

## Window Function :

- Performs a calculation across a set of table rows that are somehow related to the current row. 
- This is comparable to the type of calculation that can be done with an aggregate function. 
- But unlike regular aggregate functions, use of a window function does not cause rows to become grouped into a single output row — the rows retain their separate identities. Behind the scenes, the window function is able to access more than just the current row of the query result.
