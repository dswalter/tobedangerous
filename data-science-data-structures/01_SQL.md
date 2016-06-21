No matter how your data are structured, you will need to know SQL, (Structured Query Language).

First things first: SQL is a relational database model based on mathematical set theory (remember intersections and unions? If not, we'll get there below). Every database you use will be an implementation of the language, so each has its little quirks, which you can look forward to learning about when it's relevant.

SQL is based on tables and the relationships between entries in those tables. Let's start with the canonical sales example. Let's say you have a table you have been keeping


SELECT customer_name, order_total from orders;
