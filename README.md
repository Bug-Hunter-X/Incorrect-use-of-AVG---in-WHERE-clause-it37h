This example demonstrates a common error in SQL queries involving the use of aggregate functions like AVG() within the WHERE clause.  The provided SQL query attempts to filter employees based on whether their salary is greater than the average salary of the 'Sales' department.  However, aggregate functions are not directly allowed within a WHERE clause without using subqueries or CTEs, resulting in a syntax error. The solution illustrates how to correctly implement the query.