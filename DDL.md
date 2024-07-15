**DDL (5 commands- CREATE, ALTER, sp_rename, DROP, TRUNCATE)**

**Data Definition Language (DDL) **is used to define database objects such as tables, synonyms, views, procedures, functions, triggers, etc. that means DDL statements are used to alter/modify a database or table structure and 
schema but nothing related to table.

1. **CREATE**  -> This command will create table

**SYNTAX**
CREATE TABLE TABLE_NAME(<COLUMN_NAME1> <DATATYPE> [SIZE], <COLUMN_NAME2> <DATATYPE> [SIZE],<COLUMN_NAME3> <DATATYPE> [SIZE]...);

e.g
CREATE TABLE EMPLOYEE(ID INT, NAME VARCHAR(20),SALARY DECIMAL(6,20));

