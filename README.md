# sql-concepts-examples

# SELECT

**SELECT** is used to select columns we want to view and **From** is the table from which those column name lives

**Syntax**

SELECT * FROM table_name;

**Renaming column names** using AS keyword(eg if we want to have spaces in the names of the results)

SELECT column_name AS "Column Name"
  FROM table_name;

  e.g SELECT region AS "East region" from Country_Details;

  where 
  region is the name of the column

  upated name is in the double quotes " ", if not put in double quotes then it will start treating as a separate object which will result in an error.

  Country_Details is the name of the table

# LIMIT

limit is a simple way to keep the limit on no of records getting returned from the queries. It also helps in returning the result faster by limiting record.

**Syntax**
  SELECT * FROM table_name **LIMIT** 100

Above query will return 100 rows
