# KPI Definitions

This document defines the key performance indicators (KPIs) used in the Tableau Sales Performance Dashboard.

---

# 1. Total Sales

## Definition
Total revenue generated from all completed customer orders.

## Formula
Total Sales = SUM(Sales)

## Business Importance
Measures overall business revenue performance and growth.

---

# 2. Total Profit

## Definition
Net profit earned after accounting for costs and discounts.

## Formula
Total Profit = SUM(Profit)

## Business Importance
Indicates overall profitability and operational efficiency.

---

# 3. Total Orders

## Definition
Total number of unique customer orders processed.

## Formula
Total Orders = COUNTD(Order ID)

## Business Importance
Measures sales activity and transaction volume.

---

# 4. Total Customers

## Definition
Total number of unique customers who placed orders.

## Formula
Total Customers = COUNTD(Customer ID)

## Business Importance
Helps evaluate customer reach and market penetration.

---

# 5. Sales by Segment

## Definition
Distribution of total sales across customer segments.

## Segments Included
- Consumer
- Corporate
- Home Office

## Business Importance
Helps identify the most valuable customer segments.

---

# 6. Sales by State

## Definition
Total sales generated across different U.S. states.

## Visualization Type
Geographical Map

## Business Importance
Supports regional performance analysis and market identification.

---

# 7. Sales by Category

## Definition
Sales comparison across product categories.

## Categories Included
- Technology
- Furniture
- Office Supplies

## Business Importance
Identifies high-performing product categories.

---

# 8. Sales by Sub-Category

## Definition
Detailed analysis of product performance within categories.

## Business Importance
Helps detect profitable and underperforming products.

---

# 9. Top Customers

## Definition
Customers generating the highest sales contribution.

## Formula
Top N customers ranked by SUM(Sales)

## Business Importance
Supports customer retention and relationship strategies.

---

# 10. Sales by Managers

## Definition
Regional sales performance grouped by assigned managers.

## Business Importance
Helps evaluate managerial performance and regional effectiveness.

---

# 11. Return Analysis

## Definition
Analysis of returned orders using the Returns dataset.

## Formula
Returned Orders = COUNT(Returned = 'Yes')

## Business Importance
Helps monitor operational quality and customer satisfaction.

---

# 12. Profit Growth Metrics

## Metrics Included
- Profit CY (Current Year)
- Profit PY (Previous Year)

## Business Importance
Supports year-over-year profitability comparison.

---

# Conclusion

The KPIs in this dashboard were selected to provide a balanced view of:
- revenue performance
- profitability
- customer behavior
- regional trends
- operational effectiveness

Together, these metrics help stakeholders make informed business decisions through interactive visual analytics.
