# RESTAURANT_MANAGEMENT_SYSTEM_
This project is a Restaurant Management System built using SQL. It is designed to manage and organize restaurant operations such as menu listings, customer details, table reservations, and order processing. The database demonstrates efficient use of relational database design and incorporates various SQL concepts including joins, subqueries, views, grouping, triggers, and table modification.

The system consists of multiple interrelated tables:

menuitems – Stores menu details like item names, categories, and prices.

restaurant_tables – Maintains information about each dining table, its seating capacity, and current status (available, reserved, or occupied).

customers – Holds customer personal and contact details. An additional address field is added later using the ALTER TABLE command.

orders – Records customer orders along with order dates, table numbers, and total amounts. It connects customers and tables using foreign keys.

reservation – Tracks table reservations made by customers with their confirmation status.

order_changes_log – Keeps an automatic log of order updates whenever the total amount is changed. This is managed through a trigger.

The project also includes several SQL operations to illustrate key database functionalities:

Joins are used to combine customer and order information for reporting.

Subqueries identify customers who spent above the average order value.

Views (like customer_orders_view) simplify data retrieval and analysis.

Group By operations summarize each customer’s total spending.

Triggers automate data tracking for updates to maintain data integrity.

Overall, this project provides a clear example of how a structured SQL database can support restaurant operations — from tracking customers and reservations to managing menus and monitoring order activity — while demonstrating practical SQL techniques and database relationships.
