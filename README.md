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


### Business Objectives
KPIs:
- Total Revenue: The total sales revenue generated.
- Order Quantity: The total number of units sold.
- Total Profit: The total profits gotten from sales.
#### Business Problems:
- Revenue Distribution by Region:
     - Requirement: Analyze which countries and states generate the most revenue.
     - Objective: Target specific regions for promotional campaigns to boost sales in high-revenue areas and identify underperforming regions for 
improvement.
- Which age groups does our product mostly appeal to :
     - Requirement: Group the customers into age groups, eg. less than 25yrs as "Youth", 24-35yrs "Young Adult", more than 35yrs "Adult“ and then 
check which age group patronizes the most?
     - Objective: Tailor marketing strategies to target specific age groups and genders, optimizing product appeal for the key demographic segments.
- Product Popularity:
   - Requirement: Assess how different subcategories of products perform in terms of sales volume.
   - Objective: Use insights to refine product offerings, adjust inventory, and promote best-selling items to maximize profit.
- Sales Seasonality:
    - Requirement: Identify trends in sales across different times of the year and correlate them with external factors like holidays or cycling season.
    - Objective: Plan inventory and marketing efforts according to seasonal peaks and troughs, ensuring sufficient stock during high-demand periods 
and reducing excess inventory during low-demand months.

### Tools Used & Data Sources
- Excel for
   - Data cleaning 
   - Analysis
   - Visualization
     
- Data Source: Sports sales dataset spanning six years

### Data Cleaning & Methodology
- Handling Missing Values: Most of the colums has missing values, Age column were replaced using the average and the other missing values were deleted due to the absence of unique identifiers.
- Removing Duplicates:The dataset has no unique colum like the colum Id so duplicates were removed by highlighting the whole column.
- Ensuring Data Consistency: misspell were corrected to ensure data consistency.
- Creating an Age Category: Using the IF function, the age were categorize into different group from the age column their by creating the age category column.
- Creating a Calendar Table: Calendar table was created in power query in excel and linked to the fact table for better time-based analysis.
- Using Power Pivot for KPIs: Calculated Key performance indicators (KPIs) such as the Total Revenue, Total Orders and Total Profits were calculated using calculated measures in Power Pivot.

#### Insights & Visualizations
### Revenue by Region 
A map chart was used to visualize this making use of the calculated total revenue across different country.
- Australia: Generated the highest revenue ($1.7M) across five (5) States.
   - New South Wales is the highest-performing state.
   - Tasmania is underperforming and requires attention.
     
- United States: Generated $1.5M across twenty-two (22) states.
  - California is the highest revenue generator.
  - Other States ness improvement.

- Canada: Generated $1M across three (3) states.
  - British Columbia performed best.
  - Alberta and Ontario need improvement.
    
- United Kingdom: Generated $800K but operates only in England.
  
- France: Generated $500K across 16 states, but still requiring significant improvement across all States.

- Germany: Generated $700K across six states, and also needs better strategies for growth.

### Age Group & Gender Analysis
A doughnut chart was used to analyze revenue by age category.
- Our product appeal more to the Adult followed by the Young Adults.
- Adults (Primary customers)
   - Generated $54.8M, significantly above the average of $34.1M.
   - They are the most engaged demographic leading to the fact that our product appeal appeal more to them
   - Female patronize the more than the male with a 7% differences.
- Young Adults (Secondary customers):
   - Generated $34.2M, aligning with the benchmark.
   - Male patronize more than Female with a 3% difference
- Youths (Low engagement):
   - Generated the least revenue of, below the average benchmark.
   - Male patronize more than Female with a 4% difference
- Gender-based analysis:
   - Female customers contributed $53.8M.
   - Male customers contributed $48.4M.
- This Indicates a slightly higher female engagement in purchasing sports products and also showing that our product appeal to them.

### Product Popularity
A bar chart was used to analyze revenue by product subcategory.
- Among all the product sold Bike generated more revenue followed by Accessories and lastly Clothing.
- Indicating that the business initially focused on bike products before expanding. 
- Bikes most popular product:
   - Road Bikes generated the highest revenue followed by Mountain Bikes.
- Accessories
   - Helmets generates more revenue followed by Tires & Tubers while cleaners generates the lowest.
- Cleaner 
   - Jersey generate more while Socks is the least.
     
### Sales Seasonality
A line chart was used to analyze the seasonal sales trend for the month while column chart were used for the season.
Though the store experience a downward sales trend because of holiday and cycling period March still generate the highest revenue.
- Peak Sales Periods:
   - March with ($15.1M) had the highest monthly revenue and making up 10% of total revenue, followed by December which shows that their increase is due holiday demand.
   - Spring season ($32.7M) generated the higest revenue in the season which is the begining of cyclying period.
   - December sales increased due to holiday demand.
- Low Sales Periods:
   - July to October had lower sales.
     
### Recommendations
- Regional Expansion & Marketing
  - More stores should be open in other states in the United Kingdom inorder to increase sales
  - United States and Austrialia perform well overall, underperforming states in this country and other country need targeted market surveys to identify issues and improve strategies.
- Billboard Advertising 
  - Utilize billboard ads for awareness in different regions so that people will get to known where their stores are located in each states and country.  

- Age-based Marketing Strategies
- Adults (Primary Customers)
  - Utilize email marketing e.g., fitness tips, new arrivals etc, in marketing to them.
  - Offer home delivery services to accommodate busy work schedules seeing that most of these people are busy with work.
  - Family bundles should be introduce to encourage bulk purchases.
  - Develop a user-friendly website with customer reviews to encourage them to easily access the store online and also be encouraged by other people's review.
- Young Adults
  - Focus on social media marketing (TikTok, Instagram for videos; Facebook for ads; YouTube for video & reviews and Twitter for reviews).
  - Partner with influencers to advertist the product to drive engagement.
  - Introduce installment payment options for affordability and encourage more people who can not pay once patronize the store.
- Youths 
  - Stock more stylish & colorful sportswear to attract the youths.
  - Offer designer bikes to make cycling more appealing.
    
- Product Strategy
- Inventory Management
   - Increase inventory for best selling products like the Road and Mountain Bikes so it will always be avaliable.
   - More research should be carried out before putting discount on underperforming products.
   - Bundle bikes with accessories or clothing at discounted rates.
- Promotional Strategies:
   - Leverage social media and email marketing for displaying products and new arrivals.
   - Focus on best-selling products while working out other strategy to enhance sales performance of the low performing products.
     
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
