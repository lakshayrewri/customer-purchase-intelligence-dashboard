--1. Avg Purchases

 Avg Purchases = 
 AVERAGE('public customer'[purchase_amount])

--2. Avg Ratings

 Avg Rating = 
 AVERAGE('public customer'[review_rating])

--3. Total_customers

 Total Customers = 
 COUNT('public customer'[customer_id])

--4. Total Revenue

 Total Revenue = 
 SUM('public customer'[purchase_amount])