# SQL
- Structured Query Language (SQL)
- CRUD 
- C : CREATE
- R :READ
- U : UPDATE
- D : DELETE

## SYNTAX FOR CREATE 

 - to Create Database : `CREATE DATABASE DateBase_Name ;`
 - to Create Table : `CREATE Table TableName( columnName1 DataType, columnName2 DataType ,....)`
 - Adding  new Entities : `Insert into table_name (column1,column2) values (value1,value2); `

## SYNTAX FOR READ 
- To get All data from Table Name : `SELECT * FROM TABLE_NAME ;`
- Distinct eliminate duplicate values
- Syntax for distinct : `SELECT DISTINCT name from TABLE_NAME ;`
- WHERE is like  if condition : `SELECT  name from Table_Name where id = ? `
-  NOT OPERATOR   `!= , NOT , < >`
-  OR OPERATOR  ` SELECT * from table_name where id = num1 or id = num2  `
-  AND OPERATOR `SELECT * FROM TABLE_NAME where firstName = val1 AND lastName = val2`
-  LIKE has 2 WildCard ` '_ ' Exactly one occurance of one charactor`   ` '%' any number of occurance`
-  NULL ` isNull and isNotNull`
-  OrderBy : SQL by default sorts stores data sortedaccording to Primary Key in ascending form
-  LIMIT Clause : Limit is need to limit no of rows that a query return

## SYNTAX FOR UPDATE
-  to Update Data : `UPDATE  TABLE_NAME SET column_name = value where condition ;`
-  Don't update Primary key
-  By default SQL uses safe mode to protect data

## SYNTAX FOR DELETE 
- to Delete data : `DELETE FROM TABLENAME where condition`
- Drop the entire Table : `DROP TABLE table_name; `
- The TRUNCATE TABLE command deletes the data inside a table, but not the table itself :   `TRUNCATE TABLE TABLE_NAME;`
