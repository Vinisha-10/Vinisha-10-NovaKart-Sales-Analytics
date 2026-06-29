What is Data Modeling?

Data modeling is the process of creating a visual blueprint or structural framework that defines how data is stored, organized, and related to other data in a database.



What is a Primary Key?

A Primary Key (PK) is a unique identifier for a specific record in a table. It ensures that every row is distinct and cannot contain null (empty) values (e.g., CustomerID in a Customers table).



What is a Foreign Key?

A Foreign Key (FK) is a column in one table that links to the Primary Key of another table. It establishes and enforces a link or relationship between the data in the two tables.



What is a Fact Table?

A Fact Table stores the quantitative, measurable metrics or measurements of a business event (e.g., SalesAmount, Quantity, Discount). It usually sits at the center of an analytics model and contains mostly numbers and foreign keys.



What is a Dimension Table?

A Dimension Table stores the descriptive attributes or context surrounding a business event—answering the who, what, where, and why (e.g., customer names, product categories, store locations).



What is a Star Schema?

A Star Schema is a data modeling design where a central Fact Table is directly connected to surrounding Dimension Tables. Visually, this setup radiates outward to resemble the shape of a star.



Why is a Star Schema preferred for BI (Business Intelligence)?

Faster Query Performance: It minimizes complex database joins, allowing reports and dashboards to load significantly faster.



Simplicity for Users: The structure is highly intuitive, making it easy for business users to write queries and build their own reports.



Native BI Optimization: Analytics tools like Power BI, Tableau, and Excel are specifically designed and optimized to work best with a star schema layout.



Efficient Aggregations: It allows BI tools to quickly slice, dice, sum, and average massive amounts of data across different categories.

