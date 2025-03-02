# Structured-Query-Language-SQL-
Basics of SQL

#Query
1.AS : Rename
2.DISTINCT : Give unique values only
3.WHERE :  used to filter records. It is used to extract only those records that fulfill a specified condition.
4.LIKE is a special operator used with the WHERE clause to search for a specific pattern in a column.
5.The percentage sign % is another wildcard character that can be used with LIKE.
6.% is a wildcard character that matches zero or more missing characters in the pattern

LIKE c% finds any values that start with the letter ‘c’
LIKE %c finds any values that end with the letter ‘c’
LIKE %re% finds values that have ‘re’ in any position
LIKE _a% finds any values that have the letter ‘a’ in the second index
LIKE a_%_% finds any values that start with ‘a’ and are at least 3 characters in length.
LIKE a%r finds any values that start with ‘a’ and end with ‘r’.

7.It is not possible to test for NULL values with comparison operators, such as = and !=.
Instead, we will have to use these operators:
IS NULL
IS NOT NULL

8.BETWEEN: used in a WHERE clause to filter the result set within a certain range
9.AND
 operator displays a row if all the conditions are true.

OR
 operator displays a row if any condition is true.

 10.DESC is a keyword used in ORDER BY to sort the results in descending order (high to low or Z-A).

ASC is a keyword used in ORDER BY to sort the results in ascending order (low to high or A-Z).

11.
LIMIT
 is a clause that lets you specify the maximum number of rows the result set will have.

12.A 
Preview: Docs Returns different output based on the conditions of each statement.
CASE
 statement allows us to create different outputs (usually in the 
Preview: Docs Every SQL query will begin with the SELECT command to fetch data from one or more tables.
SELECT
 statement). It is SQL’s way of handling if-then logic.


 13.Preview: Docs Loading link description
COUNT()
: count the number of rows
SUM()
: the sum of the values in a column
MAX() /
MIN()
: the largest/smallest value
AVG()
: the average of the values in a column
ROUND()
: round the values in the column

