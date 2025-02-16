# Furniture Sales Dashboard

In this project, I have used a public dataset that to analyze the sales and profit for the organisation from 2014 to 2017 across various parameters such as different timelines, as input by the user including year, month and qtr. The first page of the dashboard focuses on a high-level trend summary and enables the user to select the metric they want to review. The page also provides a TOP 5 subcategory table to get a quick understanding of the business sales in just a glance. 

The second page is a more detailed analysis of user input metric (Sales, Qty and Profit) across the geographic region. The page also gives a breakdown of how each category is tracking for a selected metric over a selected timeline. 

The third page is a detailed summary that breaksdown sub-category performance. The report page depicts the pareto principle that enables users to understand the distribution of sales and profit for all the subcategories. 

I have included the dataset and a powerbi desktop file (.pbix) in the repository. Feel free to download the *Furniture Sales Data.pbix* file and open it using PowerBI Desktop. 

Here is a quick overview of the fields available in the dataset: 

| Column Name     | Column Type | Definition                         |
|-----------------|-------------|------------------------------------|
| Date            | Date        | Date of the transaction            |
| Customer Name   | Text        | Name of the customer               |
| State           | Text        | State (customer location)          |
| Category        | Text        | Product category                   |
| Sub-Category    | Text        | Product Sub category               |
| Product Name    | Text        | Product name                       |
| Sales           | Decimal     | Sales ($)                          |
| Quantity        | Integer     | Quantity                           |
| Profit          | Decimal     | Profit from the transaction ($)    |

		
		



## Overview

This interactive Power BI dashboard provides a comprehensive analysis of sales performance across different categories, time periods, and regions. It presents key metrics such as total sales, profit, and unit volumes while allowing users to explore trends and perform deeper analysis using filters.

---

## Page 1: Overall Trends Analysis

![Trends](https://github.com/user-attachments/assets/59190f1e-baea-413a-8da6-72de903c7dc6)


**Key Insights:**
- **Total Sales & Profit Performance**:  
  The company generated $2.30M in sales, with a profit of $286.40K, indicating a profit margin of 12.47%.  
  A total of 38K units were sold across different categories.

- **Top 5 Sub-Categories by Volume & Profit**:  
  - The highest-selling sub-category by volume is Binders (5,974 units), followed by Phones, Storage, Chairs, and Tables.  
  - The most profitable sub-category is Copiers ($55.6K profit), followed by Phones, Accessories, Paper, and Binders.

- **Category Trends (2014-2017)**:  
  Technology is the fastest-growing category in both sales and profit, while Office Supplies and Furniture show steady growth.  
  The line chart highlights consistent sales growth across all categories, with Technology outperforming Furniture and Office Supplies in 2017.

**Possible Business Actions:**
- Increasing investment in high-performing sub-categories like Phones and Copiers could maximize profitability.
- Monitoring the declining performance of tables, as it has lower sales volume and negative profit (-$17.7K).
- Expanding the market for Office Supplies and Furniture, which have stable but slower growth.

---

## Page 2: Geographic and Time-Based Analysis

![Geography](https://github.com/user-attachments/assets/059fa4af-667d-4f01-acf4-69189fbb36cd)


**Key Insights:**
- **Sales by State**:  
  A geographic breakdown provides a state-wise view of total sales, allowing businesses to identify high-revenue locations and potential markets for expansion.

- **Quarterly Sales Trends (Across Categories)**:  
  Sales performance varies across quarters, with Technology consistently leading across all four quarters.  
  Q4 shows peak sales, suggesting strong demand during the year-end, potentially due to holiday promotions or business spending.

**Possible Business Actions:**
- Optimizing inventory and marketing strategies for peak demand in Q4 to maximize revenue.
- Targeting underperforming states with marketing and promotional efforts to boost sales.
- Analyzing sales dips in certain quarters to understand potential causes and address demand fluctuations.

---

## Page 3: Sub-Category Performance & Pareto Analysis (80/20 Rule)

![Pareto](https://github.com/user-attachments/assets/09e09d7e-68c2-42e2-93df-99d800b289aa)


**Key Insights:**
- **Cumulative Sales & Profit Contribution**:  
  The Pareto Analysis (80/20 Rule) reveals that a few key sub-categories drive most of the sales and profit.  
  Top contributors to total sales include Phones, Chairs, Storage, and Binders, while Copiers, Phones, and Accessories contribute the most to profit.  
  Some sub-categories (e.g., Tables and Supplies) contribute negative profit, which may require pricing or cost structure adjustments.

- **Cumulative Percentage Analysis**:  
  80% of total sales come from a small subset of sub-categories, reinforcing the Pareto Principle.  
  The visualization of cumulative profit shows outliers that negatively impact profitability, highlighting areas for cost reduction or pricing optimization.

**Possible Business Actions:**
- Prioritizing high-contribution sub-categories (Phones, Copiers, Binders) for promotions, stock management, and investment.
- Reassessing pricing and cost structures for low-profit or negative-profit categories like Tables.
- Using data-driven forecasting and supply planning strategies to optimize inventory and reduce holding costs for low-performing sub-categories.

---

## Conclusion  
This dashboard effectively visualizes sales trends, category performance, and regional insights, enabling businesses to make data-driven decisions. By leveraging these insights, the business can optimize pricing strategies, improve profitability, and enhance market positioning.

**Data Source**: [Kaggle.com](https://www.kaggle.com)
