# E-commerce Analysis Project

## Overview

This project focuses on leveraging data analytics techniques to derive actionable insights from an e-commerce sales dataset. The analysis aims to enhance business decision-making by identifying sales trends, segmenting customers, evaluating product performance, and predicting future sales patterns. These insights can be used by businesses to optimize inventory, tailor marketing strategies, and improve customer engagement.

## Dataset

The dataset contains transactional records of an e-commerce business, providing information on invoices, products, customers, and sales across multiple countries. The dataset includes the following columns:

- **InvoiceNo**: Unique identifier for each transaction/invoice.
- **StockCode**: Unique code for each product.
- **Description**: Textual description of the product.
- **Quantity**: Number of products purchased (can be negative for returns).
- **InvoiceDate**: Timestamp of the transaction.
- **UnitPrice**: Price of a single unit of the product.
- **CustomerID**: Unique identifier for the customer.
- **Country**: The country where the transaction occurred.

## Project Tasks

### Task 1: Data Preprocessing
- **Check for Missing Values and Duplicates**: Handle missing values and remove duplicates.
- **Convert InvoiceDate Column to DateTime Type**: Ensure the InvoiceDate column is in the correct datetime format.
- **Remove Negative Values**: Check and remove rows with negative values in the Quantity or UnitPrice columns.
- **Create a TotalPrice Column**: Calculate the total price for each transaction by multiplying Quantity and UnitPrice.

### Task 2: Exploratory Data Analysis (EDA)
- **Statistical Summary**: View statistical summaries for numerical columns.
- **Top 10 Selling Products**: Identify the top 10 selling products by quantity.
- **Total Revenue**: Calculate the total revenue generated.
- **Number of Transactions**: Calculate the total number of transactions.

### Task 3: Time Series Analysis
- **Monthly Sales Trends**: Analyze monthly sales trends to identify peak and off-peak months.

### Task 4: RFM Analysis & Customer Segmentation
- **Recency, Frequency, Monetary (RFM) Analysis**: Segment customers based on their purchasing behavior.
- **Customer Segmentation**: Classify customers into High-Value, Medium-Value, and Low-Value segments.

### Task 5: Product Category Analysis
- **Sales and Revenue by Category**: Analyze sales and revenue by product category.
- **Top Categories by Revenue**: Visualize the top categories by revenue.

### Task 6: Geographical Analysis
- **Sales Distribution by Country**: Analyze sales distribution by country and identify top revenue-generating countries.

### Task 7: Customer Behavior Analysis
- **Order Quantity Distribution**: Plot the distribution of order quantities.
- **Quantity vs. TotalPrice**: Create a scatter plot of Quantity vs. TotalPrice.
- **Average Daily Sales**: Calculate and plot average daily sales throughout the week.

### Task 8: Moving Average Forecast
- **7-Day Moving Average**: Calculate and visualize the 7-day moving average of daily sales.

### Task 9: Summary Dashboard Creation
- **Key Insights Dashboard**: Create a dashboard summarizing key insights from the analysis.

### Task 10: Optimize Data Processing
- **Performance Comparison**: Compare the performance of loops and vectorized operations for data processing tasks.

### Task 11: Report Generation
- **Summary Report**: Generate a summary report with key insights and recommendations.

## Key Insights

1. **Monthly Sales Trends**: November has the highest sales, while February has the lowest.
2. **Top Selling Products**: The top 10 selling products by quantity were identified, with detailed descriptions.
3. **Customer Segmentation**: Customers were segmented into High-Value, Medium-Value, and Low-Value categories based on RFM analysis.
4. **Product Category Analysis**: The "Fine Art, Collectibles, Crafts & Sewing" category generates the highest revenue.
5. **Geographical Analysis**: The United Kingdom contributes the majority of the revenue, with the top 3 countries accounting for over 90% of total revenue.
6. **Customer Behavior**: Most sales occur on Fridays and Tuesdays, with low sales on weekends.
7. **Moving Average Forecast**: The 7-day moving average provides a smoothed trend of daily sales, highlighting seasonal spikes.

## Recommendations

1. **Inventory Optimization**: Focus on stocking high-demand products, especially during peak months like November.
2. **Marketing Strategies**: Tailor marketing campaigns to target High-Value and Medium-Value customers with personalized offers.
3. **Geographical Focus**: Allocate more resources to high-revenue-generating countries like the United Kingdom.
4. **Customer Engagement**: Implement re-engagement campaigns for Low-Value customers with high recency to bring them back.
5. **Seasonal Promotions**: Plan promotional events during high-sales periods to maximize revenue.

## Tools and Libraries Used

- **Python**: Primary programming language for data analysis.
- **Pandas**: Data manipulation and analysis.
- **NumPy**: Numerical computations.
- **Seaborn & Matplotlib**: Data visualization.
- **Plotly**: Interactive visualizations.
- **Scikit-learn**: Machine learning and statistical modeling.

## How to Run the Code

1. **Install Dependencies**: Ensure you have Python installed along with the necessary libraries (`pandas`, `numpy`, `seaborn`, `matplotlib`, `plotly`).
   ```bash
   pip install pandas numpy seaborn matplotlib plotly
   ```
2. **Download the Dataset**: Place the dataset (`data.csv`) in the same directory as the script.
3. **Run the Script**: Execute the Python script to perform the analysis.
   ```bash
   python ecommerce_analysis.py
   ```

## Report

A detailed summary report with key insights and recommendations can be found [here](https://docs.google.com/document/d/1en7sZBYdmLaObd7OM2ygVSmHhKkDQ3n3/edit?usp=sharing&ouid=115575227701801776440&rtpof=true&sd=true).

## Conclusion

This project provides a comprehensive analysis of an e-commerce dataset, offering valuable insights into sales trends, customer behavior, and product performance. The findings can help businesses make data-driven decisions to optimize operations, enhance customer engagement, and boost revenue.
