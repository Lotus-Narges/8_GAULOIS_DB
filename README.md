# WHAT I LEARNED:

## - The definition of database (DB)
## - How to create, read, update & delete the DB
## - Relational DB & Non-Relational DB
## - Tables & Keys in SQL (Primary Key, Foreign Key, Composite Key)
## - SQL --> A language which is used to interact with RDBMS(Relational database management system)
## - Connecting to phpMyAdmin
## - Creating Tables
## - Inserting data to tables
## - definition of Query and how to interact with database
## - Functions in SQL
## - Wild cards in SQL
## - UNION in SQL
## - JOINS in SQL
INNER JOIN: returns rows when there is a match in both tables.

LEFT JOIN: returns all rows from the left table, even if there are no matches in the right table.

RIGHT JOIN: returns all rows from the right table, even if there are no matches in the left table.

FULL JOIN: combines the results of both left and right outer joins.

The joined table will contain all records from both the tables and fill in NULLs for missing matches on either side.

SELF JOIN: joins a table to itself as if the table were two tables, temporarily renaming at least one table in the SQL statement.

CARTESIAN JOIN: returns the Cartesian product of the sets of records from the two or more joined tables.

## - Nested queries
## - Notion of "ON DELETE" in SQL


# HAVING
La condition HAVING en SQL est presque similaire à WHERE à la seule différence que HAVING permet de filtrer en utilisant des fonctions telles que SUM(), COUNT(), AVG(), MIN() ou MAX().

SELECT colonne1, SUM(colonne2)
FROM nom_table
GROUP BY colonne1
HAVING fonction(colonne2) operateur valeur

Cela permet donc de SÉLECTIONNER les colonnes DE la table “nom_table” en GROUPANT les lignes qui ont des valeurs identiques sur la colonne “colonne1” et que la condition de HAVING soit respectée.

Important : HAVING est très souvent utilisé en même temps que GROUP BY bien que ce ne soit pas obligatoire.
