# Sales-Analysis-PySpark

Here’s a detailed version of the description following the format you requested:

---

## Project Overview

This project demonstrates the application of **PySpark** for analyzing and visualizing sales data. By leveraging PySpark’s distributed computing capabilities, the goal was to derive actionable insights from large-scale transactional data. The project integrates data from multiple sources, processes it efficiently, and uses various aggregation techniques to derive key performance indicators (KPIs) that help businesses make data-driven decisions. Interactive dashboards and visualizations are created to make the findings easily accessible and interpretable.

## Goals

The primary goals of this project are:
1. To process and analyze large datasets efficiently using PySpark.
2. To calculate key performance indicators (KPIs) for sales data, including customer spending, category-wise sales, and sales trends.
3. To identify popular menu items based on customer transactions.
4. To present findings in an intuitive and interactive manner using visualizations and dashboards.
5. To provide insights that can inform business strategy and decision-making.

## What We Have Done

In this project, the following tasks were accomplished:
1. **Data Integration**: We joined sales data with menu details using the `product_id` to create a unified dataset for analysis.
2. **Data Aggregation**: We calculated important KPIs, including:
   - Total amount spent by each customer.
   - Sales distribution by food category.
   - Monthly, quarterly, and yearly sales trends.
   - Top 5 most ordered menu items.
3. **Visualization**: Interactive dashboards were created to visualize the insights derived from the data, such as:
   - Customer-level spending analysis.
   - Sales trends across different time periods.
   - Popular items and category-wise spending.
4. **Data Analysis**: We used PySpark’s powerful aggregation functions to process and analyze data at scale.

## Insights We Got

The key insights derived from the analysis include:
1. **Customer Spending**: Customers like A and B spent the most, with amounts of $4260 and $4440 respectively.
2. **Sales Trends**: Sales reached their peak during Q3, driven by seasonal promotions and events.
3. **Popular Menu Items**: The most frequently ordered items were identified, which can guide stock and marketing decisions.
4. **Category-wise Insights**: The project highlighted which food categories (e.g., drinks, desserts) contributed the most to total sales.
5. **Trends in Time**: Monthly, quarterly, and yearly trends revealed how sales fluctuated over time, allowing for better forecasting.

## Technology Used

The technologies and tools used in this project include:
- **Python**: For implementing the logic and scripting.
- **PySpark**: For distributed data processing and handling large datasets.
- **Databricks**: For running PySpark workflows and creating interactive visualizations and dashboards.
- **Jupyter Notebook**: For development, testing, and sharing the analysis.
- **SQL**: For querying and aggregating data efficiently within the PySpark framework.

---

This structure should provide a clear and concise summary of the project. Let me know if you would like to adjust any section!
