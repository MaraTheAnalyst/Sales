# Sales

### Project Overview

This data analysis project explores product sales and revenue trends across Canada, Australia, United Kingdom, France, United States, and Germany between 2011 and 2016. The goal is to uncover marketing patterns over the six-year period and gain deeper insights into the company’s target audience.

<img width="1915" height="861" alt="Sales Visualization 1" src="https://github.com/user-attachments/assets/05c6285d-b926-463b-be35-4b0500d69192" />

<img width="1914" height="846" alt="Sales Visualization 2" src="https://github.com/user-attachments/assets/c88bd929-832c-41ff-a83c-66e6cb54fcbf" />


Objectives:
- Identify the target audience based on purchase behavior
- Determine the best-selling product category
- Calculate the total revenue generated per year
- Analyze the total revenue by country

By analyzing this data, we aim to provide actionable insights that can support marketing strategies and optimize product distribution across regions.

### Data Source
Sales Data: The primary dataset used for this analysis is the “Sales.xlsx” file, containing detailed information about every product bought and essential details on the customers like their age, gender, country and city. 

### Tool Used
Microsoft Excel 

### Data Cleaning
To prepare the dataset for accurate analysis, the following cleaning steps were carried out:
- Handled Missing Values: Identified and addressed any missing or null entries that could interfere with the integrity of the analysis.
- Removed Duplicates and Irrelevant Columns:
  - Duplicate records were eliminated to avoid double-counting.
  - Unnecessary columns that did not contribute to the analysis—such as identifiers or overly detailed attributes—were removed for clarity and focus.
- Recalculated Inaccurate Figures: Some calculated fields such as Cost, Revenue, and Profit were reviewed and corrected using the appropriate formulas:
    - *Cost = Order Quantity × Unit Cost*
    - *Revenue = Order Quantity × Unit Price*
    - *Profit = Revenue – Cost*
      
These steps ensured that the dataset was clean, consistent, and reliable for further analysis.

### Data Analysis
The Pivot Table feature in Excel was used extensively to perform the following analyses:
- Total Revenue by Country and Year: Summed up revenue figures to identify top-performing countries and peak sales years.
- Best-Selling Product Category: Evaluated product categories to determine which generated the highest sales volumes and revenue.
- Customer Demographics Analysis:
  - Broke down sales by Customer Gender and Age Group to understand purchasing behavior across different customer segments.
- Trend Analysis Over Time:
  - Tracked yearly revenue trends to uncover patterns, growth rates, and seasonal performance.

Overall, PivotTables allowed for flexible summarization and easy comparison of data across multiple dimensions such as time, geography, product category, and customer demographics.

### Visualization
Column Charts were created to present key findings in a visually engaging and easy-to-understand format. These charts helped to:
- Identify Best-Selling Products: Highlighted the top-performing product categories and sub-categories based on total revenue and quantity sold.
- Understand the Target Audience: Showed how factors such as age, gender, and location influenced purchasing behavior.
- Pinpoint High-Performing Regions and Profitable Years: Made it easy to spot which countries and years generated the most revenue, helping to guide strategic business decisions.

The visualizations provided clear insights that complemented the pivot table analysis, making the data more actionable and presentation-ready.

### Report/Findings:
The following results were obtained:
- 2015 recorded the highest total revenue, followed by 2016, indicating peak sales performance during these periods.
- Bikes emerged as the best-selling product category, contributing significantly to total sales.
- Target Audience:
  - The majority of purchases were made by customers aged 25 to 64, across both genders.
  - A smaller, yet notable portion of customers under 25 years also made purchases, indicating emerging interest from a younger demographic.
- Top-Performing Markets:
  - The United States led in sales revenue, followed by Australia.
  - Canada recorded the lowest revenue, suggesting opportunities for targeted marketing or reevaluation of strategy in that region.

### Recommendations:
Based on the findings, the following actions are recommended:
- Capitalize on Peak Sales Years: Analyze what worked in 2015 and 2016 (marketing, pricing, campaigns) and replicate those strategies to drive future growth.
- Focus on Bikes: Increase inventory, promote bike bundles, and launch loyalty programs to capitalize on the best-selling category.
- Target Core Demographics: Direct marketing toward ages 25–64 across both genders. For customers under 25, use discounts and social media to boost engagement.
- Strengthen Regional Strategies:
  - United States & Australia: Expand distribution and marketing efforts.
  - Canada: Reevaluate strategy—consider localized promotions or pricing adjustments.
- Promote Data-Driven Decisions: Set up dashboards, monitor sales trends, and encourage regular reviews to ensure strategies align with data insights.

### Limitation
During data cleaning, I removed duplicate entries to ensure accurate results. I also excluded irrelevant columns such as Day, Month, and Date, as they had little to no impact on the analysis.
