# Sales Insights Data Analysis Project

## Overview

This project provides actionable insights into sales performance by analyzing and visualizing key metrics using Power BI. The analysis spans various dimensions, including revenue, profit, product performance, and future forecasting, to support data-driven decision-making.

## Tools and Data

- **Tool Used**: Power BI
- **Data Source**: Sales dump (SQL format)

## Key Data Preprocessing Steps

1. Removed unwanted country data from the sales market.
2. Eliminated negative and zero sales amounts, replacing them with normalized values.
3. Converted sales figures from USD to INR.
4. Established relationships between datasets through data modeling.
5. Removed duplicate transactions for data consistency.

## Dashboard Pages and Insights

### **Page 1: Key Insights**
![image](https://github.com/user-attachments/assets/dad35aee-b9dc-4033-90cc-25fa3be9bc8d)

- **Total Sales Analysis**: 
  - Calculated total sales amount using the normalized amount column.
  - Total sales quantity and trends analyzed with a year/month slider.
- **Revenue Trends**:
  - Revenue compared across different customer types.
- **Customer Insights**:
  - Visualized top 5 customers and customer type comparisons with a pie chart.

### **Page 2: Profit Analysis**
![image](https://github.com/user-attachments/assets/c294ea21-1595-4a4e-9945-a43cffeb7343)

- **Profitability Metrics**:
  - Revenue Contribution % and Profit Contribution % plotted as a cluster bar chart by market.
- **Customer Profitability Table**:
  - Detailed view of customer-specific revenue, profit contribution, and profit margins.
  - Revenue trends incorporated.

### **Page 3: Performance Insights**
![image](https://github.com/user-attachments/assets/caba73cc-6b2e-4d80-a699-0d95322081ad)

- **Regional Performance**:
  - Bar graphs to analyze performance by region and market.
  - Comparison of current year’s gross revenue vs. last year’s revenue.
- **Dynamic Profit Margin Visualization**:
  - Interactive profit margin graph that adapts based on slider inputs (e.g., red indicates areas of concern).

### **Page 4: Product Analysis**
![image](https://github.com/user-attachments/assets/835dd240-432b-40d0-a465-fb17308a390e)

- **Product Performance**:
  - Introduced a “Low Performance” slider for filtering underperforming products.
  - Visualized revenue contribution by product type.

### **Page 5: Zone Analysis**
![image](https://github.com/user-attachments/assets/80bd4750-4fc9-454f-b6f5-d1436c9a4236)

- **Zone-Based Insights**:
  - Measures such as Year-to-Date (YTD), Yearly Growth Rate, and YTD Revenue (Previous Year) help compare zone performances over time.

### **Page 6: Forecast and Future Trends**
![image](https://github.com/user-attachments/assets/55d26ca3-1436-4f47-b565-e1922c09fec2)

- **Forecasting**:
  - Projected Revenue and Quantity metrics created for future trend tracking.
  - Forecasted YTD Revenue to compare historical data and future projections.

## Key Features

- Dynamic visualizations with interactive filters and sliders for in-depth analysis.
- Cross-comparison of customer, product, and regional performance.
- Forecasting for strategic decision-making.

## Conclusion

This Sales Insights project leverages the capabilities of Power BI to transform raw data into meaningful business insights. By addressing sales trends, profitability, and forecasting, the project equips stakeholders with the tools to identify opportunities, mitigate risks, and drive growth.
