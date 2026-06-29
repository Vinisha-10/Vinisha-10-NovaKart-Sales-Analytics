1. What is a Fact Table?
A Fact Table stores the quantitative, measurable data (metrics or "facts") of a business process, such as sales amounts, quantities sold, or transaction timestamps. It consists mostly of numbers and foreign keys that link to dimension tables.

2. What is a Dimension Table?
A Dimension Table stores the descriptive attributes (the "context") surrounding a business event, answering the who, what, where, when, and why. Examples include customer names, product categories, and store locations.

3. Why is FactSales the center of the model?
In a standard retail or business model, sales is the core event being measured. FactSales sits at the center because it holds the primary metrics (revenue, quantity) that you want to analyze, and it connects directly to all the contextual dimension tables (Customers, Products, Date) radiating outward like a star.

4. Why do we create a DimDate table?
A dedicated DimDate table is created to allow for advanced, flexible time-intelligence analysis. Instead of just relying on a raw date stamp, a date dimension breaks dates down into attributes like fiscal year, quarter, month name, week of the year, and holidays, making it easy to filter and compare business performance across specific time frames.

5. Advantages of a Star Schema
* Simple and Intuitive: Easy for business users and developers to understand and write queries against.
* High Performance: Reduces the number of complex table joins, which speeds up data retrieval and reporting.
* Optimized for BI Tools: It is the preferred, native structure for business intelligence and analytics tools like Power BI and Tableau.
* Fast Aggregations: Makes summing, averaging, and filtering large volumes of transactional data highly efficient.

