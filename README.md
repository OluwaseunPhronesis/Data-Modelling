# Data Modelling and the world of Data Analysis Expression #NGN30DaysOfLearning 

# Intodroduction
What is Data Modeling 
Data Modeling is the process of creating a visual representation of either a whole information system or parts of it to communicate connections between data points and structure
# Type of Data Modeling
- Hierarchical data models represent one-to-many relationships in a treelike format. In this type of model, each record has a single root or parent which maps to one or more child tables.
- Relational data models were initially proposed by IBM researcher E.F. Codd in 1970. They are still implemented today in the many different relational databases commonly used in enterprise computing. Relational data modeling doesn’t require a detailed understanding of the physical properties of the data storage being used.
Relational databases frequently employ structured query language (SQL) for data management. These databases work well for maintaining data integrity and minimizing redundancy. They’re often used in point-of-sale systems, as well as for other types of transaction processing.
- Entity-relationship (ER) data models use formal diagrams to represent the relationships between entities in a database. Several ER modeling tools are used by data architects to create visual maps that convey database design objectives.
- Object-oriented data models: Objects are grouped in class hierarchies, and have associated features. Object-oriented databases can incorporate tables, but can also support more complex data relationships. This approach is employed in multimedia and hypertext databases as well as other use cases.
- Dimensional data models were developed by Ralph Kimball, and they were designed to optimize data retrieval speeds for analytic purposes in a data warehouse. While relational and ER models emphasize efficient storage, dimensional models increase redundancy in order to make it easier to locate information for reporting and retrieval. This modeling is typically used across OLAP systems.
# Benefits of data modeling
Data modeling makes it easier for developers, data architects, business analysts, and other stakeholders to view and understand relationships among the data in a database or data warehouse. In addition, it can:
- Reduce errors in software and database development.
- Increase consistency in documentation and system design across the enterprise.
- Improve application and database performance.
- Ease data mapping throughout the organization.
- Improve communication between developers and business intelligence teams.
- Ease and speed the process of database design at the conceptual, logical and physical levels.

# Project Objective 
(1a)	Type of Relationships
(b)	Managing Relationships 
©	 Relationship cardinality 
(2)	The Stakeholder want to know the Highest number of Sales by Team Manger and Region (Improvement of Sales)

*To know about 
- Data Modelling 
- working with Table
- Dimensions and Hierachies

# Data sourcing 
Data was extracted from the 30Days of Learning Repro Github.com
Data link https://aka.ms/30DLDATGitHubRepo 
The folder name is “Data Modelling Dataset”

# Data Transformation
The Data was Cleaned and Transformed in Power BI Query
The Dataset was Denormalized and then been normalized it by using Hierarbfchies data modeling
To have total table of 5 (Customers, Product, Sales, Sales Rep, Location)

# Findings and Recommendation 
After all the transformation it was used to creation a simple Dashboard that show the Sales level by Manger and Region 
- Insight
•	Organic Sales Team Manager have the highest Sales while James Good will sales Team Manager have the lowest Sales
•	West Region have the highest Sales while South Region have the lowest Sales  
- Recommendation 
•	Awards should be given to Organic Sales Team Manager to motivative other Team manager
•	Since west region have the highest sales meaning, there are many Customers in that area that have interest in the product so there would been more attention in that Region 
