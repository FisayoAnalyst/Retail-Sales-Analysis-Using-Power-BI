# Retail-Sales-Analysis

### Table of Contents
[Project Overview](#project-overview)

[Objectives](#objectives)

[Dataset Overview](#dataset-overview)

[Tools Used](#tools-used)


[Data Cleaning & Transformation](#data-cleaning--transformation)

[Key Insights](#key-insights)

[Dashbaord Highlights](#dashboard-highlights)

[Recommendations](#recommendations)

[Conclusion](#conclusion)

[Files in Repository](#files-in-repository)

[What I Learned](#what-i-learned)

[Future Improvements](#future-improvements)


### Project Overview
This project presents a detailed analysis of retail sales data using **Power BI**, aimed at uncovering insights into customer behavior, product preferences, and sales performance over time. The insights derived from this project are designed to help businesses make **data-driven decisions** that optimize inventory, enhance marketing strategies, and boost revenue.


### Objectives
- Analyze customer purchasing patterns by age and gender

- Identify seasonal and weekly sales trends

- Explore product category performance and preferences

- Investigate price sensitivity and purchasing volume

- Understand transaction behavior and average order values


### Dataset Overview
**Source**: [Kaggle](https://www.kaggle.com/datasets/mohammadtalib786/retail-sales-dataset)

**Rows**: 1,000 transactions

**Columns**: 9


**Key Fields**:
- `Transaction ID`, `Date`, `Customer ID`, `Gender`, `Age`

- `Product Category`, `Quantity`, `Price per Unit`, `Total Amount`


### Tools Used
- **Power BI** – Data visualization and dashboard creation

- **Excel** – Data preprocessing and wrangling

- **Kaggle** – Dataset source


### Data Cleaning & Transformation
- Handled missing values and duplicate entries

- Standardized date formats and ensured data type accuracy

- Created custom fields such as Age Group, Workday Type, and Year

- Enhanced categorical consistency for product categories


### Key Insights
| Metric                        | Insight                                 |
| ----------------------------- | --------------------------------------- |
| **Total Sales**               | \$456,123                               |
| **Units Sold**                | 2,514 units                             |
| **Top Product Category**      | Electronics – \$155,400                 |
| **Best Performing Age Group** | 19–28 years                             |
| **Most Profitable Day**       | Saturday                                |
| **Top Sales Quarter**         | Q4 (Oct–Dec)                            |
| **Optimal Price Point**       | \$500                                   |
| **Gender Spending**           | Females: 51.06% of sales; Males: 48.94% |


### Dashboard Highlights
Built in **Power BI**, the interactive dashboard includes:

- Sales Trends by Date

- Sales by Gender & Age Group

- Top Product Categories & Price Points

- Units Sold per Transaction

- Sales by Day of the Week

*Note*: The dashboard includes slicers to filter by gender, age group, and product category for dynamic insights.

<img width="1380" height="741" alt="Retail _Sales DB" src="https://github.com/user-attachments/assets/c218e96a-21f0-4a20-9c47-35678354433f" />


### Recommendations
1. **Optimize Inventory**
- Stock popular categories (Beauty in Q1/Q4; Electronics in Q2/Q4) ahead of peak seasons.

2. **Target High-Value Demographics**
- Focus marketing on the 19–28 age group.
- Use gender-based product recommendations.
  
3. **Leverage Price Insights**
- Emphasize premium pricing around $500.
- Offer bundles or tiered pricing options.

4. **Capitalize on Shopping Patterns**
- Promote weekday offers; maximize weekend traffic with exclusive deals.

5. **Enhance Customer Retention**
- Implement loyalty programs and personalized product recommendations.


### Conclusion
The analysis revealed a consistent trend of higher sales during workdays, a strong preference for premium-priced items, and gender-based product differences. These insights can help inform better inventory planning, pricing strategies, and targeted promotions to boost revenue.


### Files in Repository
- `Retail_Sales_Analysis.pbix` – Power BI dashboard file (https://github.com/FisayoAnalyst/Retail-Sales-Analysis-Using-Power-BI/blob/main/Retail_Sales%20Analytics.pbix)

- `Retail_Sales_Data.xlsx` – Cleaned dataset (https://github.com/FisayoAnalyst/Retail-Sales-Analysis-Using-Power-BI/blob/main/retail_sales_dataset.xlsx)

- `Retail_Sales_Report.pdf` – Detailed project report. (https://github.com/FisayoAnalyst/Retail-Sales-Analysis-Using-Power-BI/blob/main/Retail%20Sales_Analysis_Report.pdf)

- `README.md` – Project summary


### What I Learned
- End-to-end dashboard creation using Power BI

- Translating raw data into actionable insights

- Communicating complex patterns through visual storytelling

- Aligning business strategy with data analysis


### Future Improvements
- Include customer segmentation for deeper personalization

- Integrate external factors (e.g., holidays, promotions)

- Expand product categorization granularity (e.g., sub-categories)

