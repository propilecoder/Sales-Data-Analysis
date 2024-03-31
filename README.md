# Sales Data Analysis Project

Welcome to the Sales Data Analysis Project! This repository contains all the necessary details and steps for analyzing sales data to uncover trends, identify top-selling products, and calculate essential revenue metrics. The insights derived from this project are intended to guide business decision-making and optimize sales strategies.

## Purpose

The goal of this project is to conduct a comprehensive analysis of sales data to identify patterns, top-performing products, and key financial indicators. These insights will enable informed decision-making and the optimization of sales approaches.

## Project Description

In this project, we delve into a large dataset of sales information to extract meaningful insights. The analysis covers sales trends over time, identification of the best-selling products, and calculation of key revenue metrics such as total sales and profit margins. The project demonstrates the ability to manipulate large datasets and derive insights that can inform data-driven recommendations for sales strategy optimization.

## Dataset Column Description

The sales dataset includes the following columns:

- `ORDER ID`
- `PRODUCT`
- `QUANTITY ORDERED`
- `PRICE EACH`
- `ORDER DATE`
- `PURCHASE ADDRESS`
- `MONTH`
- `SALES`
- `CITY`
- `HOUR`

## Execution Overview

### Data Transformation

1. **Dataset Preparation**: Initially, the dataset is downloaded and uploaded into Power BI using the 'Get Data' feature, followed by the transformation steps.
2. **Promoting Headers**: The first step involves setting the first row as the header for the dataset.
3. **Detecting Data Types**: Automatic identification and conversion of data types for each column are performed under the 'Transform' tab.
4. **Datetime Splitting**: The datetime column is split into separate date and time columns using the 'Split Column' option.

### Data Visualization

1. **Sales Trend Analysis**: A line chart is utilized to depict the trend of sales over time, with months arranged in chronological order.
2. **Best-Selling Products**: A tree map visualization highlights the best-selling products, adjusted for better visual appeal.
3. **Top 5 Best-Selling Products**: This insight is visualized using a stacked bar chart, focusing on product quantity.
4. **Top Cities by Sales**: A map visualization is used to represent sales performance across various cities.
5. **Weekly Sales Distribution**: The distribution of sales by weekdays is shown using a column chart.
6. **Month-wise Filtering**: A slicer visualization enables filtering the data by months, providing an interactive element for users.

### Revenue Metrics Calculation

1. **Total Profit**: Calculating the sum of net profits from all sales transactions.
2. **Sales Quantity**: Computing the total number of units sold.
3. **Profit Margin**: Determining the ratio of net profit to total revenue, usually expressed as a percentage.

For visualization, card types are employed to display the sum of sales, quantity sold, and profit margin, with customization options for display units and precision.

## Conclusion

This project facilitates a deep understanding of sales trends, product performance, and financial health through data analysis and visualization, supporting strategic business decisions to enhance sales effectiveness.

---
For any further details or inquiries, please feel free to open an issue or submit a pull request.
