# Home_Sales

**Spark Home Sales Analysis in Google Colab**

This project demonstrates how to use Apache Spark to analyze home sales data in Google Colab. The code performs various operations, including data loading, querying, caching, partitioning, and runtime comparisons.
Key insights were derived from the data, including:
1. The average price of four-bedroom houses sold per year.
2. The average price of homes with specific features (e.g., 3 bedrooms, 3 bathrooms, 2 floors, and >= 2,000 sqft).
3. The average price per "view" rating for homes with an average price greater than or equal to $350,000.


**Overview**
The project analyzes a home sales dataset (home_sales_revised.csv) using PySpark. Key tasks include:
Loading data from an AWS S3 bucket.
Querying the data to calculate average prices based on specific criteria.
Caching the data to improve query performance.
Partitioning the data by the date_built field and saving it in Parquet format.
Comparing runtimes for cached and Parquet data.

**Conclusion**
By applying these techniques, we can significantly improve the performance of data processing workflows, especially for large-scale datasets.
