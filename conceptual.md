### Conceptual Exercise

Answer the following questions below:

- What is PostgreSQL?

  - A highly stable object-relational database management system.

- What is the difference between SQL and PostgreSQL?

  - SQL is a query language. PostgreSQL.

- In `psql`, how do you connect to a database?
- 
  -  Using `\c`

- What is the difference between `HAVING` and `WHERE`?

  - HAVING clause is used with aggregates and WHERE is not.
  
- What is the difference between an `INNER` and `OUTER` join?

  - INNER JOIN is the default join and excludes rows that do not match the given condition. OUTER JOIN includes rows without matching rows. 
  
  - In other terms, INNER JOIN returns common information between tables and an OUTER JOIN returns information in its resulting table that the INNER JOIN returns along with the information that is not common with the other table. 

  - OUTER JOIN keeps both the original information and the information that is not related to the other table. 
  
  - `OUTER JOIN`: *Use when you want to keep all the data, not just the data related to each other.*
  
  - `INNER JOIN`: *Use when you want to keep only the data related to each other.*


- What is the difference between a `LEFT OUTER` and `RIGHT OUTER` join?
  
  - The LEFT OUTER join returns all records from the left table and the matching records from the right table. 
  
  - The RIGHT OUTER join returns all records from the right table and the matching records from the left table.

- What is an ORM? What do they do?
  
  - Object Relational Management (or mapping). They serve as a bridge between Databases and Object-Oriented Programming.

- What are some differences between making HTTP requests using AJAX 
  and from the server side using a library like `requests`?

  - Client-side requests are made within the browser in AJAX. 
  - Server-side requests are made on the server and are invisible to the client.  

- What is CSRF? What is the purpose of the CSRF token?
  
  - Cross-Site Request Forgery (CSRF) is an web security vulnerability that allows an attacker to force authenticated users to submit a request to a web application against they are currently authenticated to. 
  
  - A CSRF token is a secure random token used to prevent CSRF attacks by making it difficult for hackers to construct a valid request on behalf of the victim. The attacker cannot create valid requests to the backend server without a token.

- What is the purpose of `form.hidden_tag()`?
  
  - This is a template argument which generates a hidden field that includes a token that is used to protect the form against CSRF attacks.
