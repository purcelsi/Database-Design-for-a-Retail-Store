# Entity Relationship Diagram

BRIEF:
CA1
MODULE: Introduction to Data Analytics
WEIGHTING: 15%
LECTURER: David Hamill

OVERVIEW

For this assignment you are required to choose a retail business model from there you must create an ERD diagram and develop a complete Database. 

Add enough records for query purposes. For help generating records for your stock table you may use sites like:
•	https://www.mockaroo.com/
•	https://www.generatedata.com/ 

When creating your database think of the possible example reports/queries that your data must display and answer: (Example questions below)

YOU DO NOT NEED TO WRITE THE SQL QUERIES. BUT YOUR DATABASE TABLES MUST BE DESIGNED TO HOLD THIS INFORMATION SHOULD YOU WRITE QUERIES LIKE THIS IN THE FUTURE.
1.	What customer has spent the most money in your business?
2.	How much profit have you made in the last 30 days?
3.	How much in salaries have you paid in the last 3 months?
4.	What is the total sales grouped by months?

See the final deliverables for the exact requirements of each section, this CA will take place over the course of one week.








#Solution and Design to CA1 - The Grocery Food Store Project

Background Introduction Into Chosen Business Model
This project will be based on designing a database system for a small fictitious grocery food store. The core objective is to reorganise the company’s current data storage management system on all of their employee information and customer sales. All staff are divided between two branches and the company generates its revenue by selling food products to the customers. 
Existing Database Storage System and Requirements
Research into the business store’s underlying infrastructure, operations and processes revealed a number of key issues with its current data storage system. 
1.	Firstly, the organisation is lacking an efficient streamlined approach of keeping track of all employee’s details by relying only on a paper documentation and filing cabinet system for record information. This can be a very time-consuming and difficult task to maintain, with a high risk of causing future issues relating to data redundancy and complications with payroll if it were not managed correctly. 

2.	The company’s current checkout operation system maintains a poor record of the customers transactions history and only generates manual paper receipts. This creates a difficult and laborious task for the grocery store manager to determine how much precise profit has been made by the branch per month.  Furthermore, the company lacks an adequate record keeping system on key customer data which can be valuable for developing strategies to increase sales and improve customer satisfaction.
Solution: Design and Implement a New Database Management System
After analysing the store’s operational framework and identification of its business requirements, an Entity Relationship Diagram (ERD) was employed to design an efficient relational database management system. These models are a simple and effective way of representing the data entities being modelled and the relationships between these data entities. The following main entities were identified to be included in the new Grocery Store Database Management system: CUSTOMER, BRANCH, STAFF, STAFF_SALARY_DETAIL, STAFF_ROLE, ITEM_TRANSACTION, ITEM and PRODUCT_DESCRIPTION. The relationships between each entity tables have also been mapped to the design model, alongside their associated attributes. 
The new proposed system will store data for each branch about its employees, their payroll, a history of all customer transaction activity within the store, information on the cost and manufacture for each product and a track record system for any items that may be refunded. The database will also introduce flexibility by allowing effective and easy manoeuvre of the CUSTOMER::STAFF and CUSTOMER::ITEM_TRANSACTION relationship. Each customer will have basic information stored within the system which will be linked to their purchases. Managers can also run reports viewing which store they shopped at, what they bought, how many total transactions were conducted and how much money was spent by each customer.
In order to reduce the time and burden of paper work, the new database management system will also have information stored about the workers at each branch. All employees will have a unique ID along with other information that can easily queried from the STAFF table. The owner will be also be able to retrieve a record of their salary from a separate STAFF_SALARY_DETAIL table as well as the current job title they hold.
