## Database <br>
<i> A database is an organized collection of data. </i> <br>

## DBMS <br>
<i> DBMS stands for Database Management System.</i> <br>
<i> It is a system software responisble for creation, updation and management of the database.</i> <br>

## SQL <br>
<i> SQL stands for Structured Query Language for relational database management systems.</i> <br>
<i> It is used for retriving and maipulating databases.</i> <br>

## Table <br>
<i> Table is a organized collection of data. It is stored in the form of rows and columns. </i> <br>
<b> Columns</b><i> in a table called as fields.</i> <br>
<b> Rows</b><i> in a table called as records.</i> <br>

## Primary Key <br>
<i> It is one of the constraint which uniquely identifies each row in table. </i> <br>
<i> It does not have any </i><b> null </b><i>values.</i> <br>

## Create Database<br>
`mysql> CREATE DATABASE db_name;`
<br>

## Use database<br>
`mysql> USE db_name;` <br>

## Create Table <br>
`mysql> CREATE TABLE table_name (COLUMN1_NAME DATATYPE, COLUMN2_NAME DATATYPE, ..., COLUMNn_NAME DATATYPE);`
<br>
`mysql> CREATE TABLE STUDENTS (id UNIQUE int , name NOTNULL varchar2(15), age int);`
<br>

## Insert <br>
`mysql> INSERT INTO table_name VALUES(col1, col2, ..., coln);`
<br>
`mysql> INSERT INTO STUDENTS VALUES(1,'BILL',13);`
<BR>

## Update <br>
`mysql> UPDATE table_name SET col_name = value WHERE col_name = value;`
<br>
`mysql> UPDATE STUDENTS SET name='Pit' WHERE id=1;`
<br>

## Delete <br>
`mysql> DELETE FROM table_name WHERE col_name = value;` <br>
`mysql> DELETE FROM STUDENTS WHERE name='Pit';` <br>

## Truncate <br>
<i> It delete all the fields from the table.</i> <br>
`mysql> TURNCATE TABLE table_name;` <br>

## Like operator <br>
<i> It is used to extract only that records which match the pattern</i>
`mysql> SELECT * FROM table_name WHERE col_name LIKE 'some_patter';` <br>
`mysql> SELECT * FROM STUDENTS WHERE name='%ll%';`<br>
<i> It prints all the fields where the name containes ll in it.</i> <br>


