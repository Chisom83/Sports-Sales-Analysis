# Sports-Sales-Analysis

## Table of Contents
[Project Overview](#project-overview)


[Data Cleaning](#data-cleaning)


[Key Insights](#key-insights)


[Recommendations](#recommendations)


[Conclusion](#conclusion)

## Project Overview
This project analyzes a sports sales dataset spanning six years to evaluate business performance and identify opportunities for growth. The goal is to determine:
the best-performing regions, the age group that patronizes the business the most, sales trends over time and Product popularity.
It is important to note that  the Total revenue is used as the primary metric for this  analysis.


### Business Requriement
KPIs:
- Total Revenue: The total sales revenue generated.
- Order Quantity: The total number of units sold.
- Total Profit: The total profits gotten from sales.
#### Business Problems and Objectives
- Revenue Distribution by Region:
     - Requirement: Analyze which countries and states generate the most revenue.
     - Objective: Target specific regions for promotional campaigns to boost sales in high-revenue areas and identify underperforming regions for 
improvement.
- Which age groups does our product mostly appeal to :
     - Requirement: Group the customers into age groups, eg. less than 24yrs as "Youth", 25-35yrs "Young Adult", more than 35yrs "Adult“ and then 
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
     
- Data Source: Sports sales dataset in Microsoft Excel [download here].(https://www.microsoft.com)

### Data Cleaning 
- Handling Missing Values: Most of the colums has missing values, Age column were replaced using the average and the other missing values were deleted due to the absence of unique identifiers.
- Removing Duplicates:The dataset has no unique colum like the colum Id so duplicates were removed by highlighting the whole column.
- Ensuring Data Consistency: misspell were corrected to ensure data consistency.
- Creating an Age Category: Using the IF function, the age were categorize into different group from the age column their by creating the age category column.
- Creating a Calendar Table: Calendar table was created in power query in excel and linked to the fact table for better time-based analysis.
- Using Power Pivot for KPIs: Calculated Key performance indicators (KPIs) such as the Total Revenue, Total Orders and Total Profits were calculated using calculated measures in Power Pivot.

### Key Insights

### KPIs
#### Total Revenue
> Image
*Insight*
  
#### Order Quantity
> Image
*Insight*

#### Total Profit
> Image
*Insight*

### Business Requirement

#### Revenue by Region 
A map chart was used to visualize this making use of the calculated total revenue across different country.

<div aling="center"> <img src="https://github.com/Chisom83/Sports-Sales-Analysis/blob/main/image/Map.png"   alt="Age category" width="500"> <div></div>
     
*Insights*     
- Australia:
   - Generated the highest revenue ($32.5M) across five (5) States showing that the bussiness thrive well in this region .
   - New South Wales is the highest-performing state with $17.6M generating more of the revenue in Austriallia.
   - Tasmania is underperforming and requires attention.
     
- United States:
  - Generated $30.8M across twenty-two (22) states.
  - California is the highest revenue generator $18.0M.
  - Other States need improvement.

- Canada:
  - Generated $8.0M across three (3) states.
  - British Columbia performed best with $8.0M generating almost all the whole revenue for Canada.
  - Alberta and Ontario need urgent improvement.
    
- United Kingdom:
   - Generated $11.1M but operates only in England this gives an option for better performance if there well other stores in different States.
  
- France:
   - Generated $9.8M across 16 states, but still requiring significant improvement across all States.

- Germany:
   - Generated $10.0M across six states, and also needs better strategies for growth.

#### Age Group & Gender Analysis
A doughnut chart was used to analyze revenue by age category.

<div aling="center"> <img src="https://github.com/Chisom83/Sports-Sales-Analysis/blob/main/image/Age%20cat.png"  alt="Age category" width="500"> <div></div>
     
*Insights*     
- Our product appeal more to the Adult followed by the Young Adults.
- Adults (Primary customers)
   - Generated $54.8M, significantly above the average of $34.1M.
   - They are the most engaged demographic leading to the fact that our product appeal more to them
   - Female patronize the more than the male with a 7% differences.
     
- Young Adults (Secondary customers):
   - Generated $34.2M, aligning with the average.
   - Male patronize more than Female with a 3% difference
     
- Youths (Low engagement):
   - Generated the least revenue of 13.2M, below the average benchmark.
   - Male patronize more than Female with a 4% difference
     
- Gender-based analysis:
   - Female customers generated $53.8M as total over the period of six years.
   - Male customers generated $48.4M.
- This Indicates a slightly higher female engagement in purchasing sports products and also showing that our product appeal to them.

#### Product Popularity
A bar chart was used to analyze revenue by product subcategory.

<div aling="center"> <img src="https://github.com/Chisom83/Sports-Sales-Analysis/blob/main/image/Product.png" alt="Product" width="500"> <div></div>

*Insights*
- Among all the product sold Bike generated more revenue of $76,254,413 followed by Accessories with $16,756,678 revenue  and lastly Clothing with $9,242,274 revenue.
- Indicating that bike products are the popular products and key product of the business. Also, the business initially focused on bike products before it's expansion. 

- Bikes most popular product:
   - Road Bikes generated the highest revenue followed by Mountain Bikes.
     
- Accessories
   - Helmets generates more revenue followed by Tires & Tubers while cleaners generates the lowest.
     
- Cleaner 
   - Jersey generate more while Socks is the least.
     
#### Sales Seasonality
A line chart was used to analyze the seasonal sales trend for the month while column chart were used for the season.

<div aling="center"> <img src="https://github.com/Chisom83/Sports-Sales-Analysis/blob/main/image/Line.png"  alt="Line" width="500"> <div></div>

<div aling="center"> <img src="https://github.com/Chisom83/Sports-Sales-Analysis/blob/main/image/Season.png"  alt="Season" width="500"> <div></div>

*Insights*
Though the store experience a downward sales trend because of holiday and cycling period March still generate the highest revenue.

- Peak Sales Periods:
   - March with ($15.2M) had the highest monthly revenue and making up 15% of total revenue, followed by December with ($10.2M) which shows that their increase is due holiday demand.
   - Spring season ($33.6M) generated the higest revenue in the season which is the begining of cyclying period.

- Low Sales Periods:
   - July to October had lower sales.
     
### Recommendations
- Revenue by Region
- Regional Expansion & Marketing
  - More stores should be open in other states in the United Kingdom inorder to increase sales
  - United States and Austrialia perform well overall,but underperforming states in this country and other country need targeted market surveys to identify issues and improve strategies.
- Billboard Advertising 
  - Utilize billboard ads for awareness in different regions so that people will get to known where their stores are located in each states and country.  

- Age category Marketing Strategies
- Adults (Primary Customers)
  - Utilize email marketing e.g., fitness tips, new arrivals etc, to market their goods.
  - Offer home delivery services to accommodate busy work schedules indiviuals seeing that most of these people are busy with work.
  - Family bundles should be introduce to encourage bulk purchases of product that will increase sales.
  - Develop a user-friendly website with customer reviews to encourage their customers to easily access the store online and also be encouraged by other people's review.
- Young Adults
  - Focus on social media marketing (TikTok, Instagram for videos; Facebook for ads; YouTube for video & reviews and Twitter for reviews).
  - Partner with influencers to advertist the product to drive engagement.
  - Introduce installment payment options for affordability and encourage more people who can not pay once to patronize the store.
- Youths 
  - Stock more stylish & colorful sportswear to attract the youths.
  - Offer designer bikes to make cycling more appealing.
    
- Product Popularity
- Inventory Management
   - Increase inventory for best selling products like the Road and Mountain Bikes so it will always be avaliable.
   - More research should be carried on uderperforming product to know the best strategy to be employ.
- Promotional Strategies:
   - Leverage social media and email marketing to displaying products and new arrivals.
   - Focus on best-selling products while working out other strategy to enhance sales performance for low performing products.
     
- Sales Seasonality 
  - Inventory should be stocked up for Peak Months:March, May, June, December, and April and reduced in other month.
  - Based on Season Spring is the best period to stock goods up across all regions because it generates more revenue. Also with the fact that biking/cycling activities begins from spring.
    
### Dashboard

The dashboard includes:
  - year, gender, and product slicer for deeper analysis.
  - Interactive visualizations that enhance decision-making.

<div aling="center"> <img src="https://github.com/Chisom83/Sports-Sales-Analysis/blob/main/image/Dashboard%20(2).png" alt="Dashboard" width="900"> <div></div>

- Link to dashboard
    
### Conclusion
Sports Sales stores is performing well but their is room for more growth. By leveraging social media, targeted marketing, regional expansion, and product bundling, the store can significantly boost sales and profitability. Implementing these will help maximize revenue and optimize decision-making that will boost sales and growth to a great percentage
