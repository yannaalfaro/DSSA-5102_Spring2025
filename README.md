# Coffee Shop Sales Dataset
# 
# The Coffee Shop Sales dataset contains transactional data collected from a Point-of-Sale (POS) 
# system at a fictional coffee shop, Maven Roasters, operating in three New York City locations: 
# Astoria, Hell's Kitchen, and Lower Manhattan. The dataset covers a period from January 1, 2023, 
# to June 30, 2023, providing insights into sales trends, product performance, and store-level performance.

# Data Collection & Processing
# 
# - The data was extracted from a POS system into an Excel sheet.
# - Cleaning and transformation were performed using Python in a Jupyter Notebook.
# - All column names were standardized to lowercase.
# - Any missing values (NAs) were identified and removed.

# Dataset Structure
# 
# - Format: Single table
# - Total Records: 149,116 transactions
# - Total Fields: 11 columns
# - Date Added: October 23, 2023

# Data Fields
# 
# | Column Name         | Description                                     |
# |---------------------|-------------------------------------------------|
# | transaction_id     | Unique identifier for each transaction          |
# | transaction_date   | Date of the transaction (YYYY-MM-DD)            |
# | transaction_time   | Timestamp of the transaction (HH:MM:SS)         |
# | transaction_qty    | Quantity of items sold in the transaction       |
# | store_id          | Unique identifier for the store                  |
# | store_location    | Store name (Astoria, Hell's Kitchen, Lower Manhattan) |
# | product_id        | Unique identifier for each product               |
# | unit_price        | Price per unit of the product                    |
# | product_category  | General product category (e.g., Coffee, Tea, Pastry) |
# | product_type      | Specific type within the category (e.g., Espresso, Green Tea, Croissant) |
# | product_detail    | Detailed description of the product              |
