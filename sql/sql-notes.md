A database is a collection of tables that contain data. These may be related or not 

SELECT - extracts data from a database and returns the values that you requested for 
UPDATE - updates data in a database and uses the values that you are replacing the existing content with 
DELETE - deletes data from a database. Deletes the specified data
INSERT INTO - inserts new data into a database
CREATE DATABASE - creates a new database and uses the name and values that you specify
ALTER DATABASE - modifies a database to chnawge or update it to  the vsalues that you would like 
CREATE TABLE - creates a new table using the values that you want
ALTER TABLE - modifies a table to use the new items/values that you would like to see
DROP TABLE - deletes a table
CREATE INDEX - creates an index (search key) - 
DROP INDEX - deletes an index

An index is similar to an index in a book — it helps you find information quickly without having to scan every page.
An INDEX in SQL is an object that improves the speed of data retrieval on the DB. This helps significantly reduce the number of rows that the Datanbase has to scan before the results of a query yare returned.

SELECT DISTINCT
Returns unique values from a table. So if there are multiple of the same value then these are returned only once.

WHERE 
This helps filter out the records that are returned and that meet a specific requirement 
The following operators can be used in the Where clause:

Operator	Description	Example
=	Equal	
>	Greater than	
<	Less than	
>=	Greater than or equal	
<=	Less than or equal	
<>	Not equal. Note: In some versions of SQL this operator may be written as !=	
BETWEEN	Between a certain range	
LIKE	Search for a pattern	
IN	To specify multiple possible values for a column


ORDER BY 
This is used to filter the results set in either ascending or descending after a query is run 
