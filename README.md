# Superstore Dataset Analysis

## Overview
This project analyzes the Superstore dataset obtained from Kaggle. The objective is to explore sales and profit trends, understand key performance indicators across different dimensions such as categories, sub-categories, regions, and segments, and visualize the results effectively using Python.

## Features
The analysis includes:

1. **Dataset Overview**:
   - Importing and inspecting the dataset.
   - Checking for missing values.
   - Modifying data types for better processing.

2. **Data Transformation**:
   - Converting `Order Date` and `Ship Date` columns to datetime format.
   - Extracting day, month, and year from the `Order Date` column for time-based analysis.

3. **Analysis and Visualizations**:
   - **Sales Analysis**:
     - Total sales per month visualized as a line chart.
     - Total sales per category and sub-category visualized using bar and pie charts.
     - Sales distribution by customer segment visualized using bar and pie charts.
     - Regional sales analysis visualized using bar charts.
   - **Profit Analysis**:
     - Monthly profit trends visualized as a line chart.
     - Profit distribution by category and sub-category visualized using bar and pie charts.
     - Top 5 sub-categories by profit visualized as a bar chart.
     - Regional profit distribution visualized using pie charts.
   - **Relationship Between Sales and Profit**:
     - Scatter plot to understand the correlation between sales and profit.

## Tools and Libraries Used
- **Pandas**: For data manipulation and transformation.
- **Matplotlib**: For creating static visualizations.
- **Seaborn**: For advanced visualizations with better aesthetics.

## Steps to Run the Project
1. Clone the repository to your local machine.
2. Ensure the dataset (`Sample - Superstore.csv`) is placed in the appropriate directory.
3. Install the required libraries:
   ```bash
   pip install pandas matplotlib seaborn
   ```
4. Run the script in an environment such as Jupyter Notebook, Google Colab, or any Python IDE.

## Insights
- Identified peak sales months and regions contributing most to revenue.
- Determined the most profitable and least profitable sub-categories.
- Highlighted customer segments contributing significantly to profits.
- Established a correlation between sales and profit, aiding strategic decisions.

## Dataset
The dataset is publicly available on [Kaggle](https://www.kaggle.com/), titled **Sample - Superstore.csv**. It contains the following key columns:
- **Order Date**, **Ship Date**: Dates of order and shipment.
- **Category**, **Sub-Category**: Product categories and sub-categories.
- **Region**, **Segment**: Geographical and customer segmentation.
- **Sales**, **Profit**: Financial metrics.

## Results and Visualizations
Sample outputs include:
- Line charts for sales and profit trends.
- Bar charts for category-wise sales and profit distribution.
- Pie charts for segment-wise and region-wise contributions to profit.
- Scatter plot illustrating the relationship between sales and profit.



