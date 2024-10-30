## Joins and Union 
**Consider the Country table and Persons table that you have Created earlier Perform the following:**

### (1) Perform inner join, Left join, and Right join on the tables

*SELECT c.COUNTRY_NAME AS CONT_COUNTRY_NAME,c.POPULATION,c.AREA,P.RATING,P.COUNTRY_ID,P.COUNTRY_NAME
AS PER_COUNTRY_NAME FROM COUNTRY AS C LEFT JOIN PERSONS AS P ON C.COUNTRY_NAME=P.COUNTRY_NAME;*

*SELECT C.COUNTRY_NAME AS CONT_COUNTRY_NAME,C.POPULATION,P.COUNTRY_NAME AS PER_COUNTRY_NAME,P.F_NAME,P.L_NAME,P.RATING
FROM COUNTRY AS C RIGHT JOIN PERSONS AS P ON C.COUNTRY_NAME=P.COUNTRY_NAME;*	

*SELECT C.COUNTRY_NAME AS CONT_COUNTRY_NAME,C.POPULATION AS CONT_POPULATION,P.POPULATION,P.COUNTRY_NAME
 AS PER_COUNTRY_NAME FROM COUNTRY AS C INNER JOIN PERSONS AS P ON C.COUNTRY_NAME=P.COUNTRY_NAME;*
 
 ### (2)List all distinct country names from both the Country and Persons tables.

*SELECT DISTINCT COUNTRY_NAME FROM COUNTRY;*

*SELECT DISTINCT COUNTRY_NAME FROM PERSONS;*

### (3)List all country names from both the Country and Persons tables, including duplicates. 

*SELECT COUNTRY_NAME FROM COUNTRY;*

*SELECT COUNTRY_NAME FROM PERSONS;*

### (4)Round the ratings of all persons to the nearest integer in the Persons table.

*SELECT ROUND(rating) FROM persons;*	



 





