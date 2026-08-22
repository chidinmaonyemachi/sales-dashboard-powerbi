# Sales Performance Dashboard

## Advanced Data Analysis, KPI Development & Business Intelligence Dashboard

This project analyzes retail sales performance using **Microsoft Power BI**. Building on the Week 2 analysis, Week 3 focuses on advanced business analysis, KPI development, profitability analysis, product and customer performance, time-based analysis, and business intelligence reporting.

The objective is to transform the previous analysis into a more business-focused dashboard that helps decision-makers understand **what is driving sales, what is affecting profitability, which products and segments require attention, and where opportunities for improvement exist**.

---

## Business Problem

The analysis identified a key business challenge:

> **The company is achieving strong sales growth, but profitability is being constrained by low-margin product categories and high levels of discounting.**

Furniture generates substantial sales but relatively little profit, while higher discount levels are associated with declining and eventually negative aggregate profit margins. In addition, recent sales growth has outpaced profit growth, suggesting that revenue expansion is not translating into proportional profitability.

The analysis therefore focuses on identifying the products, categories, customer segments, regions, and discount levels that are influencing overall business performance.

---

## Business Questions

The Week 3 analysis addresses the following questions:

1. What is the overall sales and profitability performance of the business?
2. How are sales and profit changing over time?
3. Which categories and sub-categories generate the most profit?
4. Which products generate the highest and lowest profit?
5. Which products generate high sales but relatively low profit?
6. How does discounting affect profitability?
7. Which regions generate the highest sales and profit?
8. Which customer segments contribute the most revenue and profit?
9. Which areas of the business are underperforming?
10. What business problems and opportunities should management prioritize?
11. What actions can management take to improve profitability?

---

## Dataset

The project continues with the **Superstore Sales Dataset** used during Week 2, maintaining dataset continuity as required for the Week 3 project.

The dataset contains information relating to:

* Orders
* Customers
* Products
* Categories
* Sub-categories
* Sales
* Profit
* Discounts
* Regions
* States
* Customer segments
* Order dates

---

## Tools Used

* Microsoft Power BI
* Power Query
* DAX
* Microsoft Excel
* GitHub

---

## Data Preparation

Data preparation was performed using Power Query and the Power BI data model.

Key preparation activities included:

* Data type validation
* Duplicate checks
* Missing value review
* Text standardization
* Date validation
* Data transformation
* Data modeling
* Creation of calculated measures using DAX

The prepared data was then used to develop interactive visualizations and business performance measures.

---

# Key Performance Indicators

The dashboard includes meaningful KPIs designed to provide a high-level view of business performance.

| KPI                         | Purpose                                            |
| --------------------------- | -------------------------------------------------- |
| **Total Sales**             | Measures total revenue generated                   |
| **Total Profit**            | Measures total earnings                            |
| **Total Customers**         | Measures customer reach                            |
| **Average Sales per Order** | Measures average order value                       |
| **Profit Margin**           | Measures profitability efficiency                  |
| **Loss-Making Products**    | Identifies products contributing to portfolio risk |

### KPI Calculations

**Profit Margin**

`Total Profit ÷ Total Sales`

**Average Sales per Order**

`Total Sales ÷ Total Orders`

---

# DAX Measures and Calculated Metrics

The project includes calculated measures to support the dashboard analysis.

| Measure                     | Formula / Logic                                 | Purpose                           |
| --------------------------- | ----------------------------------------------- | --------------------------------- |
| **Total Sales**             | `SUM(Sales)`                                    | Measures revenue                  |
| **Total Profit**            | `SUM(Profit)`                                   | Measures earnings                 |
| **Total Orders**            | `DISTINCTCOUNT(Order ID)`                       | Measures transaction volume       |
| **Total Customers**         | `DISTINCTCOUNT(Customer ID)`                    | Measures customer reach           |
| **Profit Margin**           | `Profit ÷ Sales`                                | Measures profitability efficiency |
| **Average Sales per Order** | `Sales ÷ Orders`                                | Measures average order value      |
| **Previous Year Sales**     | Time-intelligence calculation                   | Enables previous-year comparison  |
| **Sales Growth %**          | Year-over-year change                           | Measures sales growth             |
| **Profit Growth %**         | Year-over-year change                           | Measures profitability growth     |
| **Loss-Making Products**    | Filtered count of products with negative profit | Identifies portfolio risk         |

---

# Advanced Business Analysis

## Sales Performance

The analysis evaluates overall sales performance across time, regions, categories, products, and customer segments.

The dashboard provides:

* Total sales
* Sales trends
* Sales by category
* Sales by region
* Sales by customer segment
* Top-performing products
* Customer contribution to sales

---

## Profitability Analysis

Profitability was analysed alongside sales to identify areas where strong revenue does not necessarily translate into strong earnings.

The analysis examines:

* Total profit
* Profit margin
* Profit by category
* Profit by sub-category
* Profit by region
* Product-level profitability
* Loss-making products
* Discount impact on profitability

---

# Product & Profitability Analysis

The dashboard investigates product performance using sales and profit metrics.

Analysis includes:

* Top-performing products
* Bottom-performing products
* Profit by category
* Profit by sub-category
* High-sales, low-profit products
* Loss-making products
* Discount band versus profitability
* Product performance comparisons

This analysis helps distinguish between products that generate revenue and products that generate sustainable profit.

---

# Customer & Segment Analysis

Customer performance was analysed using both revenue and profitability measures.

The analysis includes:

* Sales by customer segment
* Profit by customer segment
* Top customers by sales
* Top customers by profit
* Customer contribution to sales
* Customer contribution to profit

This approach helps ensure that customer performance is not evaluated using revenue alone.

---

# Regional Analysis

Regional performance was analysed to identify stronger and weaker geographic markets.

The dashboard includes:

* Sales by region
* Profit by region
* Profit by state
* Regional comparisons
* Geographic performance filters

This analysis helps identify regional strengths and potential areas for growth.

---

# Time-Based Analysis

Sales and profit were analysed over time to identify changes in business performance.

The analysis includes:

* Yearly sales performance
* Yearly profit performance
* Sales growth
* Profit growth
* Comparison of sales growth and profit growth

Sales increased substantially in 2016 and 2017, while profit also increased. However, in 2017, sales growth of approximately **20.4%** exceeded profit growth of approximately **14.2%**.

This suggests that revenue was growing faster than profitability and indicates a need to monitor margin performance as the business expands.

---

# Key Business Insights

### 1. Technology is the strongest profitability category

Technology generates approximately **$145.5K in profit from $836.2K in sales**, producing an overall profit margin of approximately **17.4%**.

**Business implication:** Technology represents an important source of profitable revenue and should remain a key area of focus.

---

### 2. Furniture generates high sales but weak profit

Furniture generates approximately **$742K in sales but only $18.5K in profit**, resulting in an approximate **2.5% profit margin**.

Tables and Bookcases are major contributors to the profitability problem.

**Business implication:** Revenue performance alone does not indicate strong financial performance in this category.

---

### 3. Higher discounts are associated with weaker profitability

Profitability deteriorates significantly as discounts increase. Aggregate profit margins become negative within the **21–30% discount band** and remain negative across higher discount bands.

**Business implication:** Excessive discounting may be increasing sales while reducing profitability.

---

### 4. Sales growth is outpacing profit growth

Sales grew substantially in 2016 and 2017. In 2017, sales growth was approximately **20.4%**, compared with approximately **14.2% profit growth**.

**Business implication:** The company should monitor whether continued revenue growth is being achieved at the expense of profitability.

---

### 5. Consumer is the largest revenue segment

The Consumer segment contributes approximately **50.6% of total sales**, making it the largest customer segment. However, Home Office generates a higher overall profit margin.

**Business implication:** Customer performance should be evaluated using both revenue and profitability.

---

# Business Problems and Opportunities

## Problem 1: Low Furniture Profitability

Furniture generates substantial revenue but has a relatively low profit margin.

**Evidence:** Approximately $742K sales versus $18.5K profit.

**Opportunity:** Review pricing, product mix, and discounting within Furniture, particularly Tables and Bookcases.

---

## Problem 2: Discount Impact on Profitability

Higher discount levels are associated with negative aggregate profit margins.

**Evidence:** Profit margins become negative in the 21–30% discount band and remain negative at higher discount levels.

**Opportunity:** Strengthen discount approval rules and evaluate discounts based on product and regional profitability.

---

## Problem 3: Sales Growth Outpacing Profit Growth

Revenue growth is exceeding profit growth.

**Evidence:** 2017 sales growth was approximately 20.4%, while profit growth was approximately 14.2%.

**Opportunity:** Monitor profitability alongside revenue growth and investigate products, discounts, and categories contributing to margin pressure.

---

## Problem 4: Customer Revenue Concentration

Consumer customers contribute approximately 50.6% of total sales.

**Opportunity:** Maintain the Consumer segment while developing profitable growth opportunities within Corporate and Home Office segments.

---

# Recommendations

1. **Review Furniture profitability** by examining the pricing, product mix, and discount levels of Tables and Bookcases.

2. **Review discount approval rules above 20%**, because aggregate margins become negative from the 21–30% discount band onward.

3. **Evaluate customer performance using both sales and profit** rather than relying on revenue alone.

4. **Monitor profit growth alongside sales growth** to ensure that future revenue expansion does not occur at the expense of profitability.

5. **Increase focus on profitable Technology products** while continuing to monitor their margins and sales performance.

6. **Develop Corporate and Home Office opportunities** to diversify revenue and increase sales from segments with stronger profitability.

---

# Dashboard Features

The Power BI dashboard includes:

* KPI Cards
* Sales Trend Analysis
* Profitability Analysis
* Regional Performance Analysis
* Customer Segment Analysis
* Product Performance Analysis
* Category Analysis
* Sub-category Analysis
* Top and Bottom Product Analysis
* Discount Analysis
* Interactive Slicers
* Dynamic Business Insights
* Business Risks
* Business Opportunities
* Executive Recommendations

---

# Dashboard Preview

## Main Dashboard

![Dashboard](Dashboard/Dashboard%20Screenshot.png)

## Insights Page

![Insights](images/Insight%20Page.png)

## Data Model

![Data Model](images/Data%20Modal.png)

---

# Skills Demonstrated

* Data Cleaning
* Data Transformation
* Data Modeling
* Power Query
* DAX Calculations
* KPI Development
* Time-Based Analysis
* Profitability Analysis
* Product Analysis
* Customer Analysis
* Regional Analysis
* Data Visualization
* Business Intelligence
* Business Analysis
* Dashboard Design
* Executive Reporting
* Data-Driven Recommendations

---

# Conclusion

The Week 3 analysis demonstrates that strong sales performance does not always translate into strong profitability.

Technology is the strongest profitability category, while Furniture generates significant sales but relatively weak profit. The analysis also indicates that higher discount levels are associated with declining profitability, while sales growth has recently outpaced profit growth.

The findings highlight the importance of managing **product profitability, discounting, customer mix, and profit growth alongside revenue growth**.

The resulting Power BI dashboard provides an interactive view of these performance areas and supports data-driven decision-making around pricing, product strategy, customer development, and regional growth.

---

# Project Structure

```text
Sales-Performance-Dashboard/
│
├── Dashboard/
│   └── Dashboard Screenshot.png
│
├── images/
│   ├── Insight Page.png
│   └── Data Modal.png
│
├── Sales Performance Dashboard.pbix
│
└── README.md
```

---

# How to Use the Dashboard

Users can interact with the Power BI dashboard using the available slicers and filters to investigate:

* Year
* Region
* State
* Category
* Sub-category
* Customer Segment
* Product performance

The interactive filters allow users to move from high-level business performance to more detailed product, customer, and regional analysis.

---

# Project Continuity

This Week 3 project builds directly on the Week 2 Sales Performance Dashboard.

Week 2 established the initial analysis of sales, profitability, customer segments, product categories, and regional performance.

Week 3 extends that work through:

* Advanced business analysis
* KPI development
* DAX measures
* Profitability investigation
* Product-level analysis
* Discount analysis
* Customer and segment analysis
* Time-based analysis
* Business problem investigation
* Business insights
* Data-driven recommendations

---

## Author

**Chidinma Onyemachi**

**Data Analytics | Business Intelligence | Power BI**

### Tools

Power BI • Power Query • DAX • Excel • Data Visualization • Business Analysis
