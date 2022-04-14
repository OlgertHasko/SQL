# SQL

## General Notes:

### SQL Operators
AND
OR
IN/NOT IN 
LIKE/NOT LIKE
BETWEEN AND
EXISTS/NOT EXIST
IS NULL/IS NOT NULL
Comparison operators


SQL will prioritize AND > OR regardless of the order in which you use the operators.

WHERE column_name IN (); IN allows you to input a list into the parentheses and runs faster than OR operator

LIKE ('%ar') all names ending with ar
LIKE ('ar%') all names starting with ar
LIKE ('%ar%') all names containing ar
LIKE ('mar_') returns all with mar_ with 4 letters


### Aggregate Functions
-No space after calling function
-Ignore null values unless specified 
COUNT()
SUM()
MIN()
MAX()
AVG()
