# Design and Development of a Retail Store Database System

OVERVIEW

For this project, I chose to design and develop a complete database for as Grocery Store as my retail business model of choice. 

First, I generated an ERD diagram to establish the conceptual framework of the database and understand the relationships between all of the necessary tables. 


##########################################################################


#The Grocery Food Store Project

Background Introduction Into Chosen Business Model

This project will be based on designing a database system for a small fictitious grocery food store. The core objective is to reorganise the company’s current data storage management system on all of their employee information and customer sales. All staff are divided between two branches and the company generates its revenue by selling food products to the customers. 
#Existing Database Storage System and Requirements
Research into the business store’s underlying infrastructure, operations and processes revealed a number of key issues with its current data storage system. 

1.	Firstly, the organisation is lacking an efficient streamlined approach of keeping track of all employee’s details by relying only on a paper documentation and filing cabinet system for record information. This can be a very time-consuming and difficult task to maintain, with a high risk of causing future issues relating to data redundancy and complications with payroll if it were not managed correctly. 

2.	The company’s current checkout operation system maintains a poor record of the customers transactions history and only generates manual paper receipts. This creates a difficult and laborious task for the grocery store manager to determine how much precise profit has been made by the branch per month.  Furthermore, the company lacks an adequate record keeping system on key customer data which can be valuable for developing strategies to increase sales and improve customer satisfaction.

#Solution: Design and Implement a New Database Management System
After analysing the store’s operational framework and identification of its business requirements, an Entity Relationship Diagram (ERD) was employed to design an efficient relational database management system. These models are a simple and effective way of representing the data entities being modelled and the relationships between these data entities. The following main entities were identified to be included in the new Grocery Store Database Management system: CUSTOMER, BRANCH, STAFF, STAFF_SALARY_DETAIL, STAFF_ROLE, ITEM_TRANSACTION, ITEM and PRODUCT_DESCRIPTION. The relationships between each entity tables have also been mapped to the design model, alongside their associated attributes. 
The new proposed system will store data for each branch about its employees, their payroll, a history of all customer transaction activity within the store, information on the cost and manufacture for each product and a track record system for any items that may be refunded.


Careful consideration was made to the following points below during the design and construct of the database:
1. It will be able to deal with various types of payments (CC etc) and returns etc.
2. Approriate keys (primary keys, forreign keys and constraints) would be used
3. The system will also be populated with sufficient data for query testing purposes
4. All of the chosen attributes would be comprehensible and logical
5. The database will hold relevant information regarding VAT and payment methods et CC/Invoice etc
6. The database will also hold information on Stock, Sales, Returns and Suppliers.


The following SQL reports/queriees will be generated from the final constrcucted database:
1. (View) - Show all transactions for ANY given week (you decide the dates).
2. (Trigger) - Create a Trigger that updates stock levels once a sale takes place.
3. (View) - Create a View of all stock (grouped by the supplier)
4. (Stored Procedure) - Detail and total all sales for the year, group these by each month. (A Group By with RollUp)
5. (View) - Display the growth in sales (as a percentage) for
your business, from the 1st month of opening until the end of the year.
6. (Stored Procedure) - Create a stored procedure that will display all orders by customer and their county.
7. (Stored Procedure) - Create a stored procedure that will display all returns, grouped by month.
8. (Stored Procedure) - Display a specific customersdetails and all of their relevant orders to date by passing a parameter (eg: CustomerID).
9. (Trigger) - Create a Trigger that will populate a ‘history table’ once a customers contact details have been updated.10. (View) - Create a View that will display a breakdown of (a) sales (b) profit and (c) returns for each month of the year.
11. After completing each of the individual reports, you are required to add all of the above scripts into one unique sql file that will run all of the scripts together and output the data into a Data Mart.



