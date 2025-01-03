# Bike rental shop SQL Case study
**Introduction:**
Emily is the shop owner, and she would like to gather data to help her grow the
business. She has hired you as an SQL specialist to get the answers to her
business questions such as How many bikes does the shop own by category?
What was the rental revenue for each month? etc. The answers are hidden in the
database. You just need to figure out how to get them out using SQL.

**Understanding the database:**
The shop's database consists of 5 tables:
customer
bike
rental
membership_type
membership 

**The customer table**
In the first table, customer , you'll find details about the customers of the bike rental
shop. This table contains the following columns:
id The unique ID of each customer.
name The customer's name.
email The customer's email address.

**The bike table**
In the bike table, you'll find information about bikes the rental shop owns.
This table contains the following columns:
id The unique ID of the bike.
model The model of the bike.
category The type of bike (e.g., mountain bike, road bike, hybrid, electric).
price_per_hour The rental price per hour for the bike.
price_per_day The rental price per day for the bike.
status The status of the bike (available, rented, out of service). 

**The rental table**
The rental table matches customers with bikes they have rented. This table has
the following columns:
id The unique ID of the rental entry.
customer_id The ID of the customer who rented the bike.
bike_id The ID of the bike rented.
start_timestamp The date and time when the rental started.
duration The duration of the rental in minutes.
total_paid The total amount paid for the rental.

**The membership_type table**
The membership_type table has information about the different membership types for
purchase. This table contains the following columns:
id The unique ID of the membership type.
name The name of the membership type.
description A description of the membership type.
price The price of the membership type. 

**The membership table**
The membership table has information about individual memberships purchased by
customers. This table contains the following columns:
id The unique ID of the membership.
membership_type_id The ID of the membership type purchased.
customer_id The ID of the customer who purchased the membership.
start_date The start date of the membership.
end_date The end date of the membership.
total_paid The total amount paid for the membership. 





