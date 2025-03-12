# Sports-Sales-Analysis

## Table of Contents
- Project Overview
- Tools Used & Data Sources
- Data Cleaning & Methodology
- Insights & Visualizations
- Recommendations
- Dashboard
- Conclusion

## Project Overview
This project analyzes a sports sales dataset spanning six years to evaluate business performance and identify opportunities for growth. The goal is to determine:
the best-performing regions, the age group that patronizes the business the most, sales trends over time, Product popularity
It is important to note that  the Total revenue is used as the primary metric for this  analysis.

KPIs:
▪ Total Revenue: The total sales revenue generated.
▪ Order Quantity: The total number of units sold.
▪ Total Profit: The total profits gotten from sales.
Business Problems:
▪
Revenue Distribution by Region:
Requirement: Analyze which countries and states generate the most revenue.
Objective: Target specific regions for promotional campaigns to boost sales in high-revenue areas and identify underperforming regions for 
improvement.
▪ Which age groups does our product mostly appeal to :
Requirement: Group the customers into age groups, eg. less than 25yrs as "Youth", 24-35yrs "Young Adult", more than 35yrs "Adult“ and then 
check which age group patronizes the most?
Objective: Tailor marketing strategies to target specific age groups and genders, optimizing product appeal for the key demographic segments.
▪
Product Popularity:
Requirement: Assess how different subcategories of products perform in terms of sales volume.
Objective: Use insights to refine product offerings, adjust inventory, and promote best-selling items to maximize profit.
▪ Sales Seasonality:
Requirement: Identify trends in sales across different times of the year and correlate them with external factors like holidays or cycling season.
Objective: Plan inventory and marketing efforts according to seasonal peaks and troughs, ensuring sufficient stock during high-demand periods 
and reducing excess inventory during low-demand months.

### Business Objectives
The key business objectives include:
Total Revenue: Measuring the total sales revenue generated.
Order Quantity: Evaluating the total number of units sold.
Total Profit: Calculating the total profits earned.
Tools Used & Data Sources
Tool Used: Excel (for data cleaning, analysis, and visualization)
Data Source: Sports sales dataset spanning six years

Data Cleaning & Methodology
Data Cleaning Steps:
1. Handling Missing Values:
The Age column had missing values, which were replaced using the average.
Other missing values were deleted due to the absence of unique identifiers.
2. Removing Duplicates:
Duplicates were removed since the dataset lacked a unique identifier.
3. Creating an Age Category:
Used the IF function to group ages into different categories.
4. Enhancing Analysis with a Calendar Table:
A calendar table was created and linked to the fact table for better time-based analysis.
5. Using Power Pivot for KPIs:
Calculated key performance indicators (KPIs) using calculated measures in Power Pivot.
Insights & Visualizations
Revenue Distribution by Region
A map chart was used to visualize total revenue across different regions.
Australia:
Generated the highest revenue ($1.7M).
New South Wales is the highest-performing state.
Tasmania is underperforming and requires attention.
United States:
Generated $1.5M across 22 states.
California is the highest revenue generator.
Canada:
Generated $1M across three states.
British Columbia performed best.
Alberta and Ontario need improvement.
United Kingdom:
Generated $800K but operates only in England.
Expanding to other states could improve revenue.

France:
Generated $500K across 16 states, requiring significant improvement.
Germany:
Generated $700K across six states, needing better strategies for growth.
Age Group & Gender Analysis
A doughnut chart was used to analyze revenue by age category.
Adults (Primary customers):
Generated $54.8M, significantly above the average of $34.1M.
Most engaged demographic.
Young Adults (Secondary customers):
Generated $34.2M, aligning with the benchmark.
Youths (Low engagement):
Generated the least revenue, below the $34.2M benchmark.
Gender-based analysis:
Female customers contributed $53.9M.
Male customers contributed $48.3M.
Indicates a slightly higher female engagement in purchasing sports products.
Product Popularity
A bar chart was used to analyze revenue by product subcategory.
Bikes are the most popular product:
Road Bikes generated the highest revenue.
Mountain Bikes followed closely.
Indicates that the business initially focused on bike products before expanding.
Sales Seasonality
A line chart and column chart were used to analyze seasonal sales trends.
Peak Sales Periods:
March ($15.1M) had the highest monthly revenue.
Spring season ($32.7M) generated the most revenue.
December sales increased due to holiday demand.
Low Sales Periods:
July to October had lower sales.
Recommendations
Regional Expansion & Marketing
1. United Kingdom Expansion:
Open more stores in other states beyond England to increase sales.
2. Australia & United States State-level Strategy:
While these regions perform well overall, underperforming states need targeted market surveys to identify issues and improve strategies.
3. Billboard Advertising & Workforce Improvement:
Utilize billboard ads for awareness.
Assess employee performance and implement strategic changes if needed
Age-based Marketing Strategies
1. For Adults (Main Patrons):
Utilize email marketing (e.g., fitness tips, new arrivals).
Offer home delivery services to accommodate busy work schedules.
Introduce family bundles to encourage bulk purchases.
Develop a user-friendly website with customer reviews.
2. For Young Adults:
Focus on social media marketing (TikTok, Instagram for videos; Facebook for ads; YouTube and Twitter for reviews).
Use e-commerce and WhatsApp Status for easy browsing and purchases.
Partner with influencers to drive engagement.
Introduce installment payment options for affordability.
3. For Youths (Least Engaged):
Stock more stylish & colorful sportswear to attract them.
Offer designer bikes to make cycling more appealing.
Product Strategy
1. Bike Inventory Management:
Increase stock for Road and Mountain Bikes (best-selling products).
Evaluate bike racks before deciding on discounts.
2. Bundling Strategy:
Bundle bikes with accessories or clothing at discounted rates.
3. Promotional Strategies:
Leverage social media and email marketing for new arrivals.
Focus on best-selling products.
Sales Seasonality Strategy
1. Stock Up Inventory for Peak Months:
March, May, June, December, and April require higher inventory.
2. Region-based Seasonal Planning:
Spring (March–June) is the best period to stock up across all regions.
Dashboard
The dashboard includes:
A year, gender, and product slicer for deeper analysis.
Interactive visualizations to enhance decision-making.
Conclusion
The business is performing well but has room for growth. By leveraging social media, targeted marketing, regional expansion, and product bundling, the company can significantly boost sales and profitability.
Implementing these insights will help maximize revenue and optimize decision-making for sustained growth.
