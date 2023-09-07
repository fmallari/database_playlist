### Conceptual Exercise

Answer the following questions below:

- What is PostgreSQL?
PostgreSQL is a powerful, open source object-relational database system that uses
and extends the SQL language combined with many features that safely store and scale
the most complicated data workloads. 

- What is the difference between SQL and PostgreSQL?

SQL is a programming language used to manage and manipulate relational databases. 

- In `psql`, how do you connect to a database?

\c

- What is the difference between `HAVING` and `WHERE`?

HAVING is used to check a condition after the aggregation takes place
WHERE is used to check a condition before the aggresgation takes place

- What is the difference between an `INNER` and `OUTER` join?

INNER returns comomn and matching records between the two tables
OUTER is used with FULL, LEFT or RIGHT OUTER join and will also pull similar data from opposing column 


- What is the difference between a `LEFT OUTER` and `RIGHT OUTER` join?

LEFT OUTER selects left column plus common rows in right column
RIGHT OUTER selects right column plus common rows in left column

- What is an ORM? What do they do?
Object Relational Mapping converts data between relational database and an object oriented programming language (ie; sql in flask)

- What are some differences between making HTTP requests using AJAX 
  and from the server side using a library like `requests`?

- What is CSRF? What is the purpose of the CSRF token?

Cross-Site Request Forgery is a secure random token designed to prevent issue requests from attackers (ie, encrypting passwords)

- What is the purpose of `form.hidden_tag()`?

Renders a CSRF token for each field (ie, login) 
