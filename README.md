# Financial-Risky-Products-Dashboard

##  Project Overview
The **Financially Risky Products Dashboard** is a Power BI project designed to identify inventory that poses a financial risk to the business. A custom **Risk Score** is calculated using product discount, customer rating, and stock value to measure the potential revenue at risk. The dashboard also displays the percentage of total inventory value that is financially exposed using a KPI card with conditional formatting.

---

##  Objective
The objective of this project is to help businesses identify products that are heavily discounted, poorly rated, and tied up in high-value inventory. These products represent potential financial losses and require immediate management attention.

---

##  Risk Score Formula

**Risk Score = Discount % × (1 − Rating ÷ 5) × Stock Value**

Where:
- **Discount %** represents pricing reduction.
- **(1 − Rating ÷ 5)** measures customer dissatisfaction.
- **Stock Value** represents the financial value of inventory.

---

## Financial Risk KPI

The dashboard calculates:

**Financial Risk % = (Total Risk Score ÷ Total Inventory Value) × 100**

### KPI Status
-  **Low Risk:** Below 10%
-  **Medium Risk:** 10% – 25%
-  **High Risk:** Above 25%

Conditional formatting allows managers to instantly understand the overall financial health of inventory.

---

##  Dashboard Features

- Financial Risk Percentage KPI
- Risk Status Indicator
- Risky Inventory Value by Category
- Product-wise Risk Score Analysis
- Inventory Risk Table
- Category Filter
- Interactive Product-Level Insights

---

##  Key Insights

- Identifies products with high inventory value and poor customer satisfaction.
- Highlights products where heavy discounts fail to generate customer value.
- Detects inventory that contributes most to financial risk.
- Supports proactive pricing and inventory optimization decisions.

---

##  Business Recommendations

Based on the dashboard insights, businesses should:

- **Re-evaluate pricing strategies** for heavily discounted products with low ratings.
- **Improve product quality** to reduce customer dissatisfaction and returns.
- **Optimize inventory levels** for high-risk products to minimize capital loss.
- **Clear or discontinue** consistently underperforming products to protect profitability.
- **Monitor financial risk regularly** using the KPI to ensure inventory remains healthy.

---

##  Tools & Technologies

- Microsoft Power BI
- DAX
- Power Query
- Data Modeling
- Data Visualization

---

##  Dataset

The dataset includes:

- Product Name
- Category
- Discount Percentage
- Rating
- Stock Value
- Risk Score
- Financial Risk Percentage

---

##  Dashboard Preview

<img

##  Skills Demonstrated

- Power BI Dashboard Development
- Advanced DAX Calculations
- KPI Design with Conditional Formatting
- Financial Risk Analysis
- Data Modeling
- Business Intelligence
- Interactive Reporting
- Inventory Performance Analysis

---

## Author
Charu Jain

⭐ **If you found this project useful, don't forget to star this repository!**
