
# Shield Insurance Analysis 

 * Check out the interactive dashboard: :("https://app.powerbi.com/view?r=eyJrIjoiYzI4MDJkODktMGIzZC00YmVhLWEyMmMtZTZkMGUzYTk4MzRhIiwidCI6ImM2ZTU0OWIzLTVmNDUtNDAzMi1hYWU5LWQ0MjQ0ZGM1YjJjNCJ9" )

## 1. About - Shield Insurance Company

 * It oprates in 5 big cities: Delhi NCR, Chennai, Hyderabad, Indore, and Mumbai.
 * The company has 9 different kinds of insurance policies.
 * Customers get these policies in two ways: online or offline.
    * Online mode using a mobile app or their website.
    * Offline mode customers can talk to an agent or go directly to their office.
 * People who buy policies are between 18 to 82 years old.

 ## 2. Problem Statement

 The organization is initiating a data-driven project to gain insights into customer behavior and revenue performance. They aim to enhance business understanding and decision-making through data segmentation, trend tracking, and visualization.

 ## 3. Objectives to Achive

  ### 1. Customer and Revenue Overview:
  * Identify number of customers and total revenue.
  * Track daily customer and revenue growth rates.

  ### 2. Monthly Policy Analysis:
 * Monitor month-over-month policy changes to identify trends.

  ### 3. Customer Segmentation & Revenue Analysis:
 * Segment customers by age group.
 * Analyze revenue and customer count by city and age group.

  ### 4. Trend Visualization:
 * Create a toggle/switchable view between revenue trends and customer trends over time.
 * Enable filters for sales mode, age group, city, month, and policy ID.

  ### 5. Sales Mode Insights (on a separate dashboard/page):
 * Calculate and show total customers and       revenue percentage split by sales mode.
 * Analyze monthly trend of each sales mode.

 ###  6. Age Group Insights (on a separate dashboard/page):
 * Understand how age group impacts:
   * Expected settlement
   * Sales mode
   * Policy preference

## 4. Data and Tools Used

###  Data
   * dim_date
   * dim_customer
   * dim_policies
   * fact_premiums
   * fact_settlements

 
 
  ### Tools
 * Excel
 * Power Query Editor
 * Power BI


## 5. Action Performed

  ### 1. Data Loading (Importing Data)

  * Imported CSV files from Shield Insurance into Power Query: dim_date, dim_customer, dim_policies, fact_premiums, fact_settlements

 ###  2. Data Cleaning and Transformation (Power Query Editor)

  * Remove null or duplicate values

  * Rename columns for clarity

  * Change data types (text, number, date, etc.)

  * Filter irrelevant rows

  * Create calculated columns using M language (Power Query Formula Language)

 ### 3. Data Modeling

 *  Create relationships between tables (one-to-many, many-to-one)

 * Create calculated columns and measures using DAX (Data Analysis Expressions)

 * Create hierarchies (e.g., Year → Quarter → Month)

 * Build star schema using (fact and dimension tables) 

 ### 4. Data Analysis (Using DAX)
 * Use DAX to write measures ( Total Revenue, Total Customer, Daily Revenue Growth, Daily Customer Growth)

 * Perform time intelligence ( Month over month change %, Daily Customer Growth, Daily Revenue Growth)

 * Apply filters and slicers to slice data by Sales Mode, Age Group, City, Month, Policy.

###  5. Dashboard and Report Creation (Data Visualization)

 * Use visuals like bar charts, line charts, pie charts, tables.

 * Apply slicers, filters, bookmarks, switch button

 * Customize themes, colors, fonts

 * Arrange visuals into interactive pages

### 6. Sharing and Publishing 


 * Click Publish to share on Power BI Service

 * Set up scheduled refresh for live data updates

 * Share dashboards with team members or management

 ## 6. Key Insights

 * The month of March recorded both the highest number of customers and the highest revenue

 * Delhi NCR contributes 41% of total customers and revenue.

 * Indore contributes only 7.81% of customers and 8.22% of revenue lowest among all cities, indicating a need for focused improvement.

 * Age groups 31–40 and 41–50 contribute 61% of customers and generate 63% of total revenue.

 * Age group 18–24 shows low engagement and low revenue contribution so, here is key opportunity for growth.

 * Offline agent sales contribute 55.67% of revenue, indicating strong performance . Other modes  are lagging behind and needs improvement.

 * More than half of the customers use offline agents, so we need to work on making the other modes better.

 * Offline Direct made 40M in Nov 2022, but by April 2023, it only made 10M.

 * Policies P1, P3, and P2 are most preferred by customers especially in  31-40 age group.

 * Policy from P6-P9 is least preferred by the 18-24 age group.

 * Age groups 31-40 and 65+ projected higher expected settlement revenue of 319M.



