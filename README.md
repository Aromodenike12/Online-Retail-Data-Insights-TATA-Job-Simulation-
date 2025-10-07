# Online-Retail-Data-Insights-TATA-Job-Simulation-
**Built KPI dashboards and analyzed purchasing behavior trends**

## TATA DATA VISUALIZATION: EMPOWERING BUSINESS WITH EFFECTIVE INSIGHT { FORAGE JOB SIMULATION)
### Online Retail (TATA Job Simulation)
This project is an online retail business where the CEO needs the relevant analytics and Insights that would help to evaluate the current the current business performance and suggest metrics that would enable them to make better decision in the coming in year.
### Project Overview
The aim of this project was to analyze various aspects of the online retail data for 2011 and provide insights. We seek to identify trends and make data driven recommendations with the following highlights.  
- Revenue distribution across countries and customers  
- Monthly sales trends throughout the year  
- Identifying high-performing markets and customers  
- Providing actionable recommendations for business growth .
### Data Source
The dataset that was used for this data analysis “Online Retail” was a real-world data from TATA Job Simulation (Forage) which contained detailed information on Invoice No, Invoice date, Customer Id, description, Country and Stock code about the online sales made by the company.
### Tools
- Microsoft Excel - for data cleaning and analysis  
- Power BI –final cleaning, analysing, design and visualization  
- Tableau – for Visualization
- Excel/CVS for – for data storage and initial exploration  
### Data Cleaning & Preparation
- Handled missing Customer IDs and removed duplicates  
- Corrected data types (dates, numeric values)  
- Filtered invalid transactions in Quantity and Prices (e.g., negative values, cancellations)  
- Aggregated data by Month, Country, and Customer 
- Load and transform the dataset into Power BI
### Exploratory Data Analysis (EDA)
EDA involves exploring the online retail data to answer the following key questions from the CEO of the company.
- What is the total revenue generated in his company?
-  What is the total number of their customer and how committed are they?
- How has the sales trend been in the past years where the main focus should be year 2011?
- Are there any seasonal pattern of sales or peak marks?
- How wide is our location coverage, will you like to expand your sales to other locations?
### Data Analysis
Includes some interesting code / features working with e.g Power BI
-	Checking Invalid values in Quantity and Prices
-	Qty check= If (Online Retail [Qty]<1, “Invalid”, “valid”)
-	Price check= If(Online Retail[Price]<0, “Invalid”, “Valid”)
-	Total Revenue = sales * quantity
-	Average(sales) = Avg(sales) 
-	Nos of Regions = Distinct Count (Region)  
-	Add Column (DAX) for year and month from Invoice_date
### Results & Findings are summarized as follows.
-  There was no steady increase in the sales until the last quarter  of the year where strong sales performance was recorded between the month of September to November likely due to seasonal demand.  
- United Kingdom dominates sales, but countries like Netherlands, EIRE, and Germany show promising growth.  
-  A few key customers drive a large share of revenue.  
-  Revenue was not steady on monthly bases throughout the year, highlighting a need for stronger retention strategies.  
### Recommendations
- Target High-Performing Countries: Focus marketing and logistics improvements in Netherlands, EIRE, and Germany.  
- Customer Loyalty Programs: Engage top customers with personalized offers to sustain revenue.  
- Expand Partnerships: Localized strategies in underperforming countries to improve penetration.  
- Seasonal Marketing: Replicate successful promotions from peak months across other periods.  
### Limitations
- Dataset only covers 2011, so long-term trends cannot be established.  
- Customer behaviour outside transactions (e.g., returns, satisfaction) not captured.  
- External factors such as market competition or economic conditions not included.  
### Dashboard Preview
![Dashboard Preview](images/tata_job_simulation_dashboard.jpg)


