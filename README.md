📊 Customer Shopping Behaviour Analysis
Overview

This project explores customer shopping behaviour using transactional retail data to uncover patterns in spending, subscriptions, product preferences, and purchasing behaviour.

The project was completed using Python, MySQL, and Power BI, covering the complete analytics workflow from data cleaning and exploratory analysis to SQL-based business insights, dashboard creation, report writing, and presentation design.

This project demonstrates practical Data Analytics skills relevant to Data Analyst / Business Analyst / BI Analyst roles.

Dataset

The dataset used in this project contains 3,900 customer purchase records across multiple product categories.

Dataset Summary
Rows: 3,900
Columns: 18
Domain: Retail / Customer Shopping Behaviour
Key Features
Customer Demographics: Age, Gender, Location, Subscription Status
Purchase Details: Item Purchased, Category, Purchase Amount, Season, Size, Color
Shopping Behaviour: Discount Applied, Previous Purchases, Frequency of Purchases, Review Rating, Shipping Type
Data Quality
Identified 37 missing values in the Review Rating column
Missing values were handled during data cleaning
Tools

The following tools and technologies were used in this project:

Python
Pandas
NumPy
Matplotlib
Seaborn
MySQL Server
Power BI
Jupyter Notebook
Gamma
Microsoft Word / PowerPoint
Script

The project was completed in the following stages:

1. Data Loading
Imported the dataset into Python using Pandas
Reviewed the structure and summary statistics using:
df.info()
df.describe()
2. Data Cleaning
Checked for missing values
Handled missing values in the Review Rating column using the median rating of each product category
Renamed columns to snake_case for better readability
Verified consistency between related columns
3. Feature Engineering
Created an age_group column by binning customer ages
Created a purchase_frequency_days column for behavioural analysis
4. Data Optimization
Evaluated whether discount_applied and promo_code_used were redundant
Dropped promo_code_used after validation
5. SQL Analysis

The cleaned dataset was loaded into MySQL Server for business analysis.

SQL queries were used to answer questions such as:

Which gender generated more revenue?
Which products had the highest ratings?
Are repeat buyers more likely to subscribe?
Which age groups contribute the most revenue?
Which products are most dependent on discounts?
6. Dashboard Creation

An interactive Power BI dashboard was built to present the insights visually and make the analysis easier to understand.

7. Reporting & Presentation
A detailed project report was created to document the analysis and findings
A presentation was designed to communicate key insights clearly
Dashboard

The Power BI dashboard provides a visual summary of the analysis and helps highlight key business insights.

Dashboard Highlights
Revenue overview
Customer segmentation
Subscription analysis
Product and category performance
Age group contribution
Discount and shipping behaviour


Results

This project helped uncover meaningful patterns in customer shopping behaviour and convert them into business-friendly insights.

Key Insights
Certain age groups contributed higher revenue
Subscribed customers showed different spending patterns compared to non-subscribers
Some products were highly discount-dependent
Repeat buyers were more likely to show stronger customer engagement
Product ratings helped identify top-performing products
Shipping preferences influenced customer purchase behaviour
Business Recommendations
Boost Subscriptions
Promote exclusive offers and benefits for subscribers
Strengthen Loyalty Programs
Reward repeat customers and encourage movement into the Loyal segment
Review Discount Strategy
Balance discount usage to improve both sales and profit margins
Targeted Marketing
Focus marketing efforts on high-revenue age groups and valuable customer segments
How to Run
1. Clone the Repository
git clone https://github.com/NehaYadav1997/Customer-Behaviour-Analysis.git

3. Open the Project Folder
cd Customer-Behaviour-Analysis

5. Install Required Python Libraries
pip install pandas numpy matplotlib seaborn mysql-connector-python

7. Run the Python Analysis

Open the Jupyter Notebook file:

jupyter notebook Customer_Pattern.ipynb

This notebook includes:

Data loading
Data cleaning
Exploratory Data Analysis (EDA)
Feature engineering
Data preparation for SQL
5. Run the SQL Analysis

Open MySQL Server and run the SQL script:

customer_pattern.sql

This file contains SQL queries used to analyze:

Revenue trends
Customer segments
Product performance
Subscription behaviour
Discount and shipping insights

Make sure the dataset is imported into MySQL before running the queries.

6. Open the Power BI Dashboard

Open the following file in Power BI Desktop:

customer_pattern.pbix
The Power BI dashboard was created to visualize key KPIs, customer behaviour, subscription trends, product performance, and revenue patterns.

7. View the Report

Open the project report file:

Customer Shopping Behaviour Analysis Report.docx

This document contains the complete written analysis, findings, and business recommendations.

8. View the Presentation

Open the project presentation file:

Customer-Shopping-Behavior-Analysis.pptx

This presentation summarizes the project for easy stakeholder or recruiter review.

Project Structure
Customer-Shopping-Behaviour-Analysis/
│
├── customer_shopping_behavior.csv
├── Customer_Pattern.ipynb
├── customer_pattern.sql
├── customer_pattern.pbix
├── Customer Shopping Behaviour Analysis Report.docx
├── Customer-Shopping-Behavior-Analysis.pptx
└── README.md
Conclusion

This project demonstrates the complete workflow of a Data Analytics project, from raw data to final insights and business communication.

It highlights practical skills in:

Data Cleaning
EDA
Feature Engineering
SQL Analysis
Dashboard Development
Business Reporting

This makes it a strong portfolio project for showcasing analytical and technical skills to recruiters.

Author

Neha Yadav
Aspiring Data Analyst | BI Analyst | Data Professional

LinkedIn:www.linkedin.com/in/nehayadav26
