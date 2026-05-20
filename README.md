E-commerce-product-analysis-pyspark

Project Description<br>
E-commerce Product Analysis using PySpark:<br>
This project analyzes e-commerce retail transaction data using Apache PySpark, a powerful big data processing framework. The goal is to extract meaningful insights from product sales data by performing data loading, transformation, and analysis tasks inside a Jupyter Notebook environment set up via Anaconda.<br>

Objective:<br>
To process and analyze e-commerce product data efficiently using PySpark, identifying the most expensive product and analyzing product distribution across countries.<br>

Tools & Technologies:<br>

Tool | Purpose
Apache PySpark | Big data processing & analysis
Jupyter Notebook | Interactive code execution
Anaconda | Environment & package management
Python 3 | Programming language

Tasks Performed:<br>

Load CSV Dataset: Loaded e-commerce dataset (InvoiceNo, StockCode, Description, Quantity, UnitPrice, Country) into a PySpark DataFrame<br>
Find Most Expensive Product: Identified the product with the highest UnitPrice using sorting operations<br>
Group by Country: Grouped data by Country to analyze transaction distribution<br>
Count Products per Country: Calculated total number of products sold per country using aggregation functions<br>

Dataset:<br>

Format: CSV<br>
Columns: InvoiceNo, StockCode, Description, Quantity, UnitPrice, CustomerID, Country<br>
Source: Kaggle Online Retail Dataset<br>
Size: ~1000+ records (real-world retail transaction data)<br>

Key Learnings:<br>

Setting up and using Apache PySpark in Jupyter Notebook<br>
Loading and processing CSV datasets using Spark DataFrames<br>
Performing sorting, grouping, and aggregation operations<br>
Handling real-world structured data efficiently<br>
Exporting processed results to CSV files for reporting<br>
