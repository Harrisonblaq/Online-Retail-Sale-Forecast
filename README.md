# Online Retail Sale Forecast
To develop a predictive model that classifies online retail transactions into specific categories and clusters. This will help uncover hidden patterns, improve customer segmentation, optimize inventory management, and enhance sales forecasting.

## Table Of Content
- [Project-Overview](ProjectOverview)
- [Data-Sources](DataSource)
- [Tools](Tools)
- [Data-Cleaning/Preparation](DataCleaning/Preparation)
- [Exploratory-Data-Analysis](ExploratoryDataAnalysis)
- [Data-Analysis](DataAnalysis)
- [Findings](Findings)
- [Recommendation](Recommendation)
- [Reference](Reference)


## Project Overview
This report outlines the process and insights derived from an Online retail sale forecast and clustering analysis. It discusses the methodology used, key findings and recommendations.
To develop a predictive model that classifies online retail transactions into specific categories and clusters. This will help uncover hidden patterns, improve customer segmentation, optimize inventory management, and enhance sales forecasting.
- Predictive Modeling: Build a model to classify transactions based on purchasing behaviour.
- Clustering Analysis: Identify customer and product segments using clustering techniques.
- Feature Engineering: Create meaningful features from transactional data.
- Sales Forecasting: Predict future sales trends based on historical data.
- Customer Segmentation: Group customers based on their purchasing behaviour for targeted marketing.

<img width="1233" alt="Screenshot 2025-03-07 at 06 20 07" src="https://github.com/user-attachments/assets/b87f6fce-d204-4e8c-8113-2f83fbadb785" />

<img width="1233" alt="Screenshot 2025-03-07 at 06 20 20" src="https://github.com/user-attachments/assets/14c4fae5-3461-46eb-a1ef-f80434a98025" />

## Data Sources
The primary dataset used for this analysis is the "Online Retail Sale.csv" file, containing full detail of sales from each company.

## Tools 

- Excel - Data Cleaning 
- [Download Excel Here](http://microsoftexcel.com/download)

- Python - Data Analysis and Visualization
- [Download Python Here](http://anaconda.com/download)

## Data Cleaning/Preparation
In the initial data preparation phase we performed this tasks, such as:
- Data loading and Inspection
- Converted the Online Retail sale.xlsx file to Csv.
- Handling missing values
- Data cleaning

## Exploratory Data Analysis
EDA involved exploring hidden patterns to answer key questions, such as:
- What is the Sales trend?
- What are the top-selling products?
- What are the highest purchase trends?

## Data Analysis
Including some interesting codes worked with
Importing the libraries 
- Import pandas as Pd
- import numpy as np
- import seaborn as sns
- import maplotlib.pyplot as plt
- df.head()
- dropna()
- df.info

## Findings
- The chart revealed that SET 2 TEA TOWELS I LOVE LONDON and SPACEBOY BABY GIFT SET are the highest-selling products, both of them exceeding 7,000 sales. Meanwhile, some products like 4 PURPLE FLOCK DINNER CANDLes have significantly lower sales
- The chart revealed that Q4 (Oct-Dec) has the highest sales with Q1 having the lowest sales.
November has the highest sales. The overall trend suggests a gradual increase from mid-year, peaking in December
Thursday has the highest sales, The sales are relatively stable from Monday to Wednesday but increase significantly on Thursday.
- The Sales are peak in the Afternoon. Morning sales are moderate, showing steady activity but lower than the afternoon peak. Sales decline sharply in the evening and reach the lowest point at night.
- There is a low population of Customers who buy often and tend to come back quickly (green cluster). Some customers buy occasionally and have moderate recency (Orange cluster) while customers that haven't bought in a long time and don’t buy often (Blue cluster) are high in population.
- To improve the effectiveness of the models when it comes to prediction, more features should be recorded like holiday season, discounts, viral trends or special promotions.

## Recommendation
- The Businesses should stock more of the high-demand products like SET 2 TEA TOWELS I LOVE LONDON and SPACEBOY BABY GIFT SET while reconsidering the supply of low-performing items
- The Business should increase inventory before peak sales months (September- November) and reduce stock in slower months like April and July
Promotions should be ramped up in low-sales months to smooth revenue streams
- The business should invest more in Q4 campaigns since they generate the highest returns.
- The business should boost marketing campaigns on Thursdays to maximize peak sales.
- The business should consider weekend deals to drive engagement on Saturday and Sunday
- To retain high purchase customers (Green Clusters). The Business can implement a loyalty program or exclusive discounts to reward them.
For the moderate-purchase customers (Orange clusters), the business can used personalized promotions or email reminders to increase engagement.
- Lastly, for the Low Purchase Customers (Blue segment), they need to be reactivated. The business can implement re-engagement campaigns with special offers or discounts, and use targeted ads or emails to remind them of products they previously showed interest in.

## Reference
- Pandas Official Documentation
- Explains how to convert a column to datetime format and handle errors.
- (https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.to_datetime.html)
- Handling Date and Time in Pandas – Real Python
- (https://realpython.com/python-pandas-tricks/#handling-dates-and-times-in-pandas)
- Python for Data Analysis by Wes McKinney (Book)
- The author of pandas explains best practices for data manipulation, including datetime handling.
- (https://www.oreilly.com/library/view/python-for-data/9781491957653/)
