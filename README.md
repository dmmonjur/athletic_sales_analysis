# Athletic Sales Analysis

## Overview

This project involves analyzing sales data to gain insights into the performance of athletic wear sales across various U.S. regions, retailers, and specific product categories (with a focus on women's athletic footwear). The analysis spans data from two consecutive years, 2020 and 2021, and aims to identify top-performing regions, retailers, and sales trends.

## Project Structure

The project is structured as follows:

1. **Data Import and Cleaning**
   - Two CSV files (`athletic_sales_2020.csv` and `athletic_sales_2021.csv`) containing sales data for the years 2020 and 2021 are imported.
   - The datasets are checked for consistency in column names and data types.
   - The datasets are combined into a single DataFrame.
   - The `invoice_date` column is converted to a datetime data type to facilitate time-based analysis.
   
2. **Data Analysis**
   - **Region-Based Analysis:**
     - Determine the top five regions (including state and city) that sold the most products.
     - Determine the top five regions (including state and city) that generated the most sales.
   - **Retailer-Based Analysis:**
     - Identify the top five retailers (including region, state, and city) that generated the most sales.
     - Determine which retailers sold the most women's athletic footwear.
   - **Time-Based Analysis:**
     - Identify the day with the highest sales for women's athletic footwear.
     - Determine the week with the highest sales for women's athletic footwear.

## How to Use This Repository

1. **Clone the Repository**
   ```bash
   git clone https://github.com/dmmonjur/athletic_sales_analysis.git


2. **Install Dependencies**
   ```bash
   pip install pandas

3. **Run the Analysis Open the Jupyter Notebook (athletic_sales_analysis.ipynb) and run the cells to perform the analysis.**



## Results
**Key Findings**

    Top Regions: The analysis reveals the top five regions with the highest product sales and sales revenue.
    Top Retailers: The analysis identifies the top retailers that generated the most revenue and sold the most women's athletic footwear.
    Sales Trends: The analysis highlights the specific days and weeks with the highest sales for women's athletic footwear, providing insights into peak shopping times.

## Conclusion

**The results of this analysis can be used by stakeholders to understand sales trends, optimize inventory distribution, and develop targeted marketing strategies.**

**Files in the Repository**

    athletic_sales_2020.csv - Sales data for the year 2020.
    athletic_sales_2021.csv - Sales data for the year 2021.
    athletic_sales_analysis.ipynb - Jupyter Notebook containing the data analysis.
    README.md - This file, providing an overview of the project.

