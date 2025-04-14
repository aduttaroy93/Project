# Project
Pyspark-Data-Engineering-Project ( Databricks)

Unlocking E-Commerce Insights with Databricks: 

*A Mini Project Breakdown

* I recently completed a mini project analyzing e-commerce data using Databricks and PySpark, focusing on customer and order datasets. Here’s a snapshot of the key insights and learnings:

* Key Findings:

* Customer Demographics:

The dataset spanned 8 distinct cities (e.g., Bangalore, Mumbai, Pune) with customers from diverse states like Maharashtra, Karnataka, and Tamil Nadu.

Active vs. Inactive Users: Filtered active customers to understand engagement trends.



*Data Quality Checks:

    Validated schema and inferred data types (e.g., registration_date as date, is_active as boolean).

   Used countDistinct to identify unique cities and states for geographic analysis.



*Transformations:

  -Leveraged PySpark’s DataFrame API to clean and explore data efficiently.

    -Example: Filtered active customers (is_active = True) to focus on high-potential segments.



*Technical Approach

  - Tools: Databricks, PySpark (Spark 3.3.2), and SQL-like operations.

  - Methods: Schema inference, aggregation, and filtering to derive actionable insights.



* Scalability: Demonstrated parallel processing with local[8] to handle data efficiently.




