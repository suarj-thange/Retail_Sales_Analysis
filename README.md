Retail Sales Analysis & Interactive Excel Dashboard

📌 Project Overview

This project is an end-to-end Retail Sales Analysis built entirely
in Microsoft Excel. The project starts with raw retail transaction data
and transforms it into a structured analytical dataset, PivotTables,
PivotCharts, KPIs, slicers, and three interactive dashboards.

The main objective is to understand sales performance, customer
behavior, and product performance and present the findings in an
easy-to-use dashboard format.

The workbook contains six main sections:

Raw_Data -- Original/raw transaction dataset

Data -- Cleaned and analysis-ready dataset with calculated
columns

Pivots -- PivotTables used as the analytical foundation

Sales Analysis -- Interactive sales dashboard

Customer Analysis -- Interactive customer dashboard

Product Analysis -- Interactive product dashboard

🎯 Project Objectives

The key objectives of this project are to:

Analyze overall retail sales performance.

Calculate important sales and revenue KPIs.

Understand sales trends across years, quarters, and weekdays.

Compare sales across regions, categories, brands, and sales
channels.

Analyze customer segments, age groups, and gender.

Identify product and category-level sales performance.

Analyze the impact of discounts on sales.

Build interactive dashboards using Excel PivotTables, PivotCharts,
and slicers.

Convert raw transactional data into meaningful business insights.

Demonstrate practical Excel skills required for data analyst roles.

📊 Dataset

The project uses a retail transaction dataset containing 120,000
transactions and 24,784 customers.

Original Raw Data Columns

Column                 Description

transaction_id       Unique ID for each transaction
transaction_date     Date on which the transaction occurred
customer_id          Unique customer identifier
customer_gender      Customer gender
customer_age_group   Customer age category
customer_segment     Customer segment such as New, Returning, or VIP
product_id           Unique product identifier
product_name         Product name
category             Product category
brand                Product brand
quantity             Number of units purchased
unit_price           Price per unit
discount_pct         Discount percentage
sales_amount         Sales amount after discount
payment_method       Payment method used
sales_channel        Online or In-Store
region               Sales region

🧹 Data Preparation & Transformation

The raw dataset was first organized into an analysis-ready structure.

The Data sheet contains the original fields along with additional
calculated columns used for analysis.

Additional Calculated Columns

1. Weekday

The transaction date was converted into the corresponding weekday.

Purpose:
This makes it easier to perform day-wise and weekday-based sales
analysis using PivotTables and PivotCharts.

2. Quarter

The transaction date was converted into quarterly information such as
Q1, Q2, Q3, and Q4.

Purpose:
This made it easier to perform quarter-wise sales trend analysis.

3. Year

The year was extracted from the transaction date.

Purpose:
This made it easier to perform year-wise sales comparison and
time-based analysis.

4. Actual Total

Calculated using:

Actual Total = Quantity × Unit Price

Purpose:
This represents the total product value before applying discounts and
makes it easier to analyze gross product value and discount impact.

5. Discounted Amount

Calculated using:

Discounted Amount = Actual Total × Discount %

Purpose:
This measures the amount reduced from the original product value due
to discounts.

6. Actual Sales

Calculated using:

Actual Sales = Actual Total − Discounted Amount

Purpose:
This represents the net sales value after discount and provides a
consistent measure for sales analysis.

7. Ratings

Customer/product ratings are included in the analysis-ready dataset and
can be used to understand product/customer experience alongside sales
performance.

🧮 Key Business Metrics

The workbook calculates several important KPIs.

KPI                               Value

Gross Revenue                47,996,218
Net Revenue               45,357,059.66
Discounted Amount          2,639,158.34
Total Quantity                  199,549
Average Discount %              5.4965%
Average Product Value            377.98
Total Orders                    120,000
Total Customers                  24,784

KPI values are based on the workbook data and may change if the
underlying dataset is modified or refreshed.

📈 Dashboard 1: Sales Analysis

The Sales Analysis dashboard focuses on the overall sales
performance of the business.

Main areas of analysis

Overall revenue performance

Gross Revenue

Net Revenue

Discounted Amount

Total Quantity

Total Orders

Sales trends over time

Quarterly performance

Category-wise sales

Regional performance

Sales channel analysis

Payment method analysis

Business Questions Answered

How much revenue did the business generate?

How much revenue was lost through discounts?

How are sales changing over time?

Which quarters contribute the most sales?

Which categories generate higher sales?

Which regions contribute more to revenue?

How do Online and In-Store sales compare?

Which payment methods are commonly used?

👥 Dashboard 2: Customer Analysis

The Customer Analysis dashboard focuses on customer characteristics
and purchasing behavior.

Main areas of analysis

Customer count

Customer segment

Customer gender

Customer age group

Regional customer distribution

Sales contribution by customer segment

Sales by gender

Sales by age group

Customer purchasing patterns

Sales channel behavior

Customer Segments

The dataset includes segments such as:

New

Returning

VIP

Business Questions Answered

How many customers are represented in the dataset?

Which customer segment contributes more to sales?

Which age groups generate higher sales?

How are customers distributed by gender?

Which regions contain more customer activity?

What purchasing patterns can be observed across customer groups?

📦 Dashboard 3: Product Analysis

The Product Analysis dashboard focuses on product-level and
category-level performance.

Main areas of analysis

Product category performance

Product sales

Brand performance

Quantity sold

Product value

Product ratings

Discount analysis

Category-wise revenue

Product-level comparison

Business Questions Answered

Which product categories generate the most revenue?

Which products have higher sales volumes?

Which brands contribute more to sales?

Which products receive higher ratings?

How do discounts vary across products/categories?

Which categories combine strong sales with higher quantities?

🔄 PivotTables & PivotCharts

PivotTables were used as the main analytical engine of the workbook.

They were created to summarize:

Revenue

Sales

Quantity

Orders

Customers

Categories

Products

Brands

Regions

Customer segments

Gender

Age groups

Years

Quarters

Weekdays

Sales channels

Payment methods

Ratings

Discounts

PivotCharts were then connected to these summaries to create visual
representations of the data.

This approach makes the dashboard dynamic and easier to filter and
analyze.

🎛️ Interactive Filters / Slicers

The dashboards include interactive slicers that allow users to filter
the analysis.

Important filters include:

Year

Region

Customer Gender

Customer Age Group

Customer Segment

Payment Method

Sales Channel

Users can select a particular filter value and the dashboard updates to
show the corresponding analysis.

For example:

Selecting a specific year and region allows the user to examine sales
performance for that particular combination.

🛠️ Tools & Technologies

Microsoft Excel

The project was created using Microsoft Excel and demonstrates practical
use of:

Excel Tables

Data Cleaning

Calculated Columns

Excel Formulas

PivotTables

PivotCharts

Slicers

KPI Cards

Conditional Formatting

Dashboard Design

Data Analysis

Interactive Filtering

Core Excel Concepts Used

Date extraction

Arithmetic calculations

Percentage calculations

Aggregation

SUM

AVERAGE

COUNT

PivotTable grouping

Filtering

Sorting

Data visualization

🔄 Project Workflow

Raw Retail Dataset
        ↓
Data Preparation
        ↓
Calculated Columns
        ↓
Analysis-Ready Dataset
        ↓
PivotTables
        ↓
PivotCharts
        ↓
KPI Creation
        ↓
Slicers & Filters
        ↓
Interactive Dashboards
        ↓
Business Insights

📁 Workbook Structure

Retail_Sales_Analysis.xlsx
│
├── Raw_Data
│   └── Original retail transaction data
│
├── Data
│   └── Cleaned and transformed dataset
│       ├── Weekday
│       ├── Quarter
│       ├── Year
│       ├── Actual_Total
│       ├── Discounted_Amount
│       ├── Actual_Sales
│       └── Ratings
│
├── Pivots
│   └── PivotTables used for analysis
│
├── Sales Analysis
│   └── Sales dashboard
│
├── Customer Analysis
│   └── Customer dashboard
│
└── Product Analysis
    └── Product dashboard

💡 Key Analytical Areas

Sales Performance

Sales performance is evaluated using gross revenue, net revenue,
quantity sold, orders, and time-based trends.

Discount Analysis

The project separately calculates the original product value, discount
amount, and final sales value to understand the effect of discounts.

Actual Total
     ↓
Discount
     ↓
Actual Sales

Time-Based Analysis

The extracted Year, Quarter, and Weekday fields make it possible to
analyze sales across different time periods.

Customer Analysis

Customer characteristics such as age group, gender, and segment are
analyzed to understand purchasing behavior.

Product Analysis

Products are analyzed by category, brand, quantity, sales value, and
ratings.

📌 Example Business Insights

The dashboard can be used to identify insights such as:

Overall revenue and order performance.

Difference between gross and net revenue.

Total value given as discounts.

Sales trends across years and quarters.

High-performing product categories.

Regional sales differences.

Customer segment contribution.

Customer age-group purchasing patterns.

Online versus In-Store performance.

Payment method distribution.

Product and brand performance.

Relationship between discounts, sales, and quantity.

The exact insight selected for a presentation should be based on the
current dashboard filters and PivotTable results.



🚀 How to Use the Workbook

Open the Excel workbook.

Start with the Raw_Data sheet to view the original dataset.

Open the Data sheet to see the transformed analysis-ready data.

Open Pivots to review the PivotTables used for calculations.

Open Sales Analysis for the sales dashboard.

Open Customer Analysis for customer insights.

Open Product Analysis for product insights.

Use the available slicers to filter the dashboards.

Select different years, regions, customer groups, channels, or
payment methods.

Observe how the dashboard visuals and KPIs change according to the
selected filters.

📷 Dashboard Preview

1. Sales Dashboard

<img width="689" height="288" alt="Sales Analysis Dashboard" src="https://github.com/user-attachments/assets/c43344a8-aca7-4cf9-ac9e-3e4befe71618" />


2. Customer Dashboard

<img width="604" height="298" alt="Customer Analysis Dashboard" src="https://github.com/user-attachments/assets/cee0f794-61b0-4e41-a0ba-6566c3097ca4" />


3.  Product Dashboard

<img width="629" height="290" alt="Product Analysis Dashboard" src="https://github.com/user-attachments/assets/f95be3f6-1173-40aa-96f3-367142b295cf" />




👨‍💻 Author

Suraj Thange

Bachelor of Engineering -- Computer Engineering
Mumbai University

⭐ Project Highlights

120,000 retail transactions

24,784 customers

6 structured Excel sheets

3 interactive dashboards

Multiple PivotTables and PivotCharts

Calculated sales and discount metrics

Interactive slicers

Time-based sales analysis

Customer segmentation

Product and category analysis

KPI-driven reporting

📜 License

This project is intended for educational and portfolio purposes.

If you use the dataset or extend this project, please verify the
original dataset's licensing and attribution requirements.

⭐ If You Find This Project Useful

If this project helps you understand Excel-based retail analytics,
consider giving the repository a ⭐ on GitHub.
