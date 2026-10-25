# Flipkart Web Scraping & Product Analytics

This project demonstrates a complete **web scraping and product analytics workflow using Python**, with a focus on e-commerce product data from Flipkart.

The project covers three product categories: **Laptops, Washing Machines, and Refrigerators**. Product information such as **brand, price, MRP, customer ratings, specifications, and category-specific attributes** is collected and processed for analysis.

### Project Workflow

**1. Web Scraping**

- Used **Requests** and **BeautifulSoup** to collect product information.
- Extracted product names, prices, MRP, ratings, and specifications.
- Organized the collected information into structured datasets.

**2. Data Cleaning & Preprocessing**

- Converted price, MRP, rating, and other fields into appropriate data types.
- Handled missing and inconsistent values.
- Cleaned product information for further analysis.

**3. Feature Extraction & Engineering**

- Extracted **brand, RAM, storage, capacity, automation type, load type, door type, and defrost type**.
- Calculated **discount amount and discount percentage** from price and MRP.
- Created additional analytical features from product specifications.

**4. Exploratory Data Analysis (EDA)**

- Performed brand-wise product analysis.
- Compared average product prices across brands and categories.
- Analyzed customer ratings and pricing patterns.
- Examined discount percentages and product characteristics.
- Studied relationships between product attributes and pricing.

**5. Data Visualization**

Created visualizations using **Matplotlib and Seaborn**, including:

- Brand-wise product counts
- Average price comparisons
- Price vs. customer rating
- Average discount percentage
- Product capacity analysis
- Automation and load-type comparisons
- Door and defrost-type analysis

**6. Dataset Export**

- Exported processed and cleaned datasets into **CSV files** for further analysis and reuse.

### Technologies Used

- Python
- Jupyter Notebook
- Requests
- BeautifulSoup
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Regular Expressions (re)

### Key Skills Demonstrated

**Web Scraping | Data Collection | Data Cleaning | Data Preprocessing | Feature Engineering | Exploratory Data Analysis | Data Visualization | Statistical Analysis | Python | Pandas | NumPy | BeautifulSoup**

### Project Outcome

The project demonstrates how raw e-commerce product information can be transformed into **structured, analysis-ready datasets** and used to identify meaningful insights related to **pricing, discounts, ratings, brands, and product characteristics**.
