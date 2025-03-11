# Sales Data Analysis Project

## Overview
This project performs an **Exploratory Data Analysis (EDA)** on a sales dataset to uncover trends, seasonal patterns, and key performance metrics. The analysis includes data cleaning, summary statistics, visualizations, and insights on top-performing products and regions.

## Dataset
The dataset contains the following columns:
- **Date**: Date of the sale transaction.
- **Product_ID**: Unique identifier for the product.
- **Product_Name**: Name of the product sold.
- **Category**: Category of the product (Electronics, Accessories, etc.).
- **Region**: Geographical region of the sale (North, South, East, West).
- **Sales_Amount**: Total sales revenue from the product.
- **Quantity_Sold**: Number of units sold.
- **Discount**: Discount percentage applied.
- **Customer_Rating**: Customer rating out of 5.

## Steps in Analysis
1. **Load and Clean Data**
   - Read the CSV file using `pandas`.
   - Handle missing values by either dropping or filling them.
   - Convert data types if necessary.

2. **Perform Summary Statistics and Exploratory Analysis**
   - Compute mean, median, and standard deviation of numerical columns.
   - Identify top-selling products and high-revenue regions.

3. **Visualize Key Metrics**
   - Create **pie charts** to show sales distribution by region.
   - Use **bar charts** to display top-selling products.
   - Generate **line plots** to observe sales trends over time.

4. **Document Insights**
   - Summarize key findings from the analysis.
   - Provide recommendations based on trends and performance.

## Installation and Requirements
To run this project, install the following Python libraries:
```sh
pip install pandas matplotlib
```

## Running the Project
1. Place the dataset (`sales_data.csv`) in the working directory.
2. Open the Jupyter Notebook (`sales_analysis.ipynb`).
3. Run each cell to perform the analysis and generate visualizations.

## Output Example
- **Pie Chart**: Displays sales distribution across different regions.
- **Bar Graph**: Highlights top-selling products.
- **Summary Report**: Key insights from the dataset.

## Conclusion
This project helps businesses understand their sales performance, optimize pricing strategies, and focus on high-revenue products and regions.

## Author
**Partha Sarathi Gogoi**

---
Let me know if you want any modifications! 🚀

