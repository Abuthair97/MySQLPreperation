# MySQLPreperation



1.What is DataBase?
Answer: DataBase is a collection of related Data

2.What are the types of DB?
- 1.Relational DB - SQL
-  2.Non Relational DB - NOSQL

 ## RelationalDB
  - We will store data in form of tables they are inter-related

## NON RelationalDB
- its just a dump of data
- they dont follow relational model
- EX: text , to do list ,key-value

## Properties of RDBMS(Relation database Management System)
-  it stores data in form of inter-related tables
-  Every row is unique (PS : Atleast one coloumn should be unique)
-  All values in coloumn have same datatype values;
-  All Values/cells should be atomic
-  Name of every coloumn should be unique

## Keys
- keys help us to uniquely identify a row

## Super keys
- Super uses a combination of coloumn to uniquely indentify a  row
- a table can have multiple super key
- a super key doesn't restrict for no of coloumns/fields

## Candidate key
- Minimum (non redundant ) columns which are required to uniquely identify a row is called Candidate key
- Candidate key is a subset of Super key

## Primary key
- Among all candidate key we choose a primary key . there is only one primary key in a table
- Data being stored according to primary key
- indexing is also made on primary key

## Composite Key
- Composite key have combination of >1 columns
- Composite key can be Super key , candidate key and primary key

## foreign key
- Foreign key is a column in a  table which refers to the column of another table
- There is no relation between foreign key and any other key



  
