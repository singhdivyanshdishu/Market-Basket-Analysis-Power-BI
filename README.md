# Market Basket Analysis Dashboard

## Overview

This project involves creating a dashboard that represents Market Basket Analysis (MBA) for a grocery store. The dashboard is created using Power BI and visualizes key metrics and insights derived from the data.

## Market Basket Analysis

Market Basket Analysis is a data mining technique used to uncover relationships between items in large datasets. It is commonly used in retail to understand the purchase behavior of customers. The key concepts in MBA include:

- **Support**: The frequency with which an itemset appears in the dataset.
- **Confidence**: The likelihood that an item B is purchased when item A is purchased.
- **Lift**: The ratio of the observed support to that expected if the items were independent.

## Dashboard Creation Steps

1. **Data Collection**: Gather transaction data from the grocery store. This data should include transaction IDs, product IDs, and timestamps.

2. **Data Transformation**: Prepare the data for analysis. This involves cleaning the data, handling missing values, and transforming it into a suitable format for MBA.

3. **Data Loading**: Import the transformed data into Power BI.

4. **Data Modeling**: Create the necessary relationships and calculated columns/measures in Power BI.

5. **Visualization**: Design the dashboard to visualize the MBA metrics. Common visualizations include:

   - Heatmaps to show the support of itemsets.
   - Bar charts for confidence levels.
   - Scatter plots to illustrate lift.

## Data Transformation

To perform Market Basket Analysis, the data needs to be transformed into a format suitable for analysis. The typical steps include:

1. **Transaction Data**: Ensure the data includes transaction IDs and product IDs.
2. **Cleaning**: Remove any duplicate transactions and handle missing values.
3. **Aggregation**: Aggregate the data to create itemsets for each transaction.
4. **Binary Representation**: Convert the data into a binary format where each row represents a transaction, and each column represents an item. A value of 1 indicates the presence of an item in the transaction, and 0 indicates its absence.

## Dashboard Preview

![image](https://github.com/user-attachments/assets/34dee4ef-5615-47ea-96fd-b716bcb5e794) <br>
![image](https://github.com/user-attachments/assets/155edcbd-9fef-42e5-b7f8-0f4c11c49c7a)



## Files

- `Market Basket Analysis.pbix`: Power BI file containing the dashboard.

## Usage

1. Open the `Market Basket Analysis.pbix` file in Power BI Desktop.
2. Review and explore the visualizations.
3. Use the slicers and filters to interact with the data and gain insights.
