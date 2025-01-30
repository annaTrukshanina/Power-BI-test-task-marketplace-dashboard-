# Power-BI-test-task-marketplace-dashboard

# Sales Analysis Dashboard

## Project Overview
This project aims to create a sales analytics dashboard that aligns with the specified technical requirements and reference design. The dashboard is designed to provide insights into key sales metrics, their dynamics, and distribution across various categories.

---

## Requirements
### Data Preparation
- **Normalize data**:
  - Handle empty and duplicate rows in the source data.
  - Ensure correct data types for all fields.
- **References**:
  - All necessary reference data tables are pre-created.
- **Date Handling**:
  - The "SPP_order_dates" do not contain all possible dates, so a custom date calendar must be created.

### Metrics to Calculate
- **Revenue (Выручка)**
- **Profit (Прибыль)**
- **Profitability (Рентабельность)**
- **Number of Clients (АКБ)**
- **Average Check (Средний чек)**
- **Logistics Costs (Затраты на логистику)**

### Visualizations
1. **Dynamics of Metrics**:
   - Display the trends of key metrics over time.
2. **Customer Segmentation**:
   - Show metrics segmented by customer types.
3. **Category Drill-Down**:
   - Allow drill-down from categories to subcategories to individual items.
4. **Geographical Distribution**:
   - Visualize data distribution on a map.

### Additional Analysis
1. **ABC Classification**:
   - Calculate and display an ABC analysis for product categories.
2. **Negative Profit Orders**:
   - Create a table highlighting managers with orders yielding negative profits, including the number of such orders.

---

## Reference Design Insights
The reference design showcases:
- **Metrics Summary**: Total revenue, profit, number of clients, average check, profitability percentage, and logistics costs.
- **Dynamic Trends**: Month-by-month metric trends.
- **Customer Segmentation**: A bar chart comparing metrics across customer segments.
- **Category Insights**: Drill-down analysis from high-level categories to individual products.
- **Map Visualization**: Regional data distribution.
- **Negative Profit Table**: Manager-wise breakdown of orders with negative profits.

---

## Steps to Complete the Project
1. **Data Preparation**:
   - Cleanse and normalize data.
   - Create a custom date calendar.
2. **Metric Calculations**:
   - Use the cleaned data to calculate all specified metrics.
3. **Dashboard Development**:
   - Create visualizations based on the reference design.
   - Implement drill-down functionality for category analysis.
   - Design a map to display regional distribution.
4. **Analysis**:
   - Perform ABC analysis.
   - Identify and highlight orders with negative profits.

---

## Tools and Technologies
- **Data Preparation**: Power Query, SQL, or Python (pandas).
- **Visualization**: Power BI.

---

## Expected Deliverables
- A fully functional Power BI dashboard meeting all requirements.
- Cleaned and normalized dataset.
- Documentation of calculations and steps for reproducibility.

---

## Notes
- Ensure all visuals are intuitive and align with the reference design.
- Validate metrics against source data for accuracy.
- Optimize the dashboard for performance with large datasets.

![image](https://github.com/user-attachments/assets/23e206f5-a8d1-4959-9af6-5526827b1a83)
