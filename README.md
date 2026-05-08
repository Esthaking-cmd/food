🍽 Food Delivery Analytics Dashboard
📌 Project Overview

The Food Delivery Analytics Dashboard is a complete end-to-end data analytics project designed to analyze food delivery operations and generate meaningful business insights from raw order data.

This project focuses on:

Data Cleaning & Preprocessing
Exploratory Data Analysis (EDA)
Feature Engineering
MySQL Database Integration
Interactive Dashboard Development
Business Insight Generation

The final output is an interactive Streamlit dashboard connected with MySQL, allowing users to analyze customer behavior, revenue trends, delivery performance, restaurant performance, and operational insights in real time.

🎯 Project Objectives

The primary objectives of this project are:

Analyze customer ordering behavior
Monitor revenue and profitability trends
Evaluate delivery efficiency
Identify operational issues causing cancellations
Analyze restaurant performance
Build a scalable analytics dashboard for business decision-making
🛠 Technologies Used
Technology	Purpose
Python	Data analysis & dashboard development
Pandas	Data cleaning & transformation
NumPy	Numerical operations
Matplotlib	Data visualization
Plotly	Interactive dashboard charts
MySQL	Database storage
SQLAlchemy	Python-MySQL connection
PyMySQL	MySQL database connector
Streamlit	Interactive dashboard application
📂 Project Structure
Food-Delivery-Analytics/
│
├── FOOD_ANALYSIS_PROJECT.ipynb
├── online_F_A.ipynb
├── app.py
├── README.md
📓 File Explanation
1️⃣ FOOD_ANALYSIS_PROJECT.ipynb

This notebook contains the initial level of data preprocessing and cleaning.

Tasks Performed
Data loading using Pandas
Initial dataset exploration
Identifying missing values
Handling invalid data
Removing duplicates
Converting data types
Basic Exploratory Data Analysis (EDA)
Data Cleaning Methods Used
isnull()
fillna()
replace()
drop_duplicates()
astype()
to_datetime()

2️⃣ online_F_A.ipynb

This notebook contains the advanced data cleaning and feature engineering process.

Tasks Performed
Advanced missing value handling
Delivery time preprocessing
Feature engineering
Data transformation
Analytical column creation
Final dataset preparation
Feature Engineering Methods Used
Weekend / Weekday classification
Distance binning
Age group categorization
Profit percentage calculation
Delivery category creation
Pandas Functions Used
groupby()
transform()
apply()
cut()
value_counts()
median()
mean()

3️⃣ app.py

This file contains the complete dashboard application.

Main Functions
Connects Python with MySQL Workbench using SQLAlchemy
Loads cleaned data from MySQL
Performs dashboard preprocessing
Creates interactive visualizations
Generates business insights using Streamlit and Plotly
🗄 Database Integration

The cleaned dataset is stored in a MySQL database for structured data management and scalable querying.

Database Features
Structured table creation
SQL-based data storage
Python-MySQL integration
Real-time dashboard querying
Database Connection

The project uses:

SQLAlchemy
PyMySQL
Example Connection
from sqlalchemy import create_engine

engine = create_engine(
"mysql+pymysql://username:password@localhost/database_name"
)
📊 Dashboard Features

The Streamlit dashboard includes:

📌 KPI Metrics
Total Orders
Total Revenue
Average Order Value
Average Delivery Time
Cancellation Rate
Average Delivery Rating

🔍 Analytical Insights
1️⃣ Customer & Order Analysis
Top spending customers
Age group vs order value analysis
Weekend vs weekday order patterns

2️⃣ Revenue & Profit Analysis
Monthly revenue trends
Impact of discounts on profit margins
High revenue cities analysis

3️⃣ Delivery Performance
Average delivery time by city
Distance vs delivery time analysis
Delivery rating vs delivery time relationship

4️⃣ Restaurant Performance
Top-rated restaurants
Cancellation rate by restaurant
Cuisine-wise performance analysis

5️⃣ Operational Insights
Payment mode preferences
Cancellation reason analysis
Business operational trends

📈 Visualization Techniques Used

The project uses multiple visualization techniques including:

Bar Charts
Line Charts
Scatter Plots
Pie Charts
Donut Charts
Box Plots
Violin Plots

Interactive visualizations are created using Plotly for a better user experience.

⚙️ Data Preprocessing Workflow
Step 1 — Raw Data Cleaning
Missing value handling
Invalid value correction
Duplicate removal

Step 2 — Feature Engineering
Month extraction
Distance categorization
Age grouping
Profit calculations

Step 3 — Database Storage
MySQL table creation
CSV import into MySQL
SQLAlchemy integration

Step 4 — Dashboard Development
Streamlit dashboard creation
Interactive filtering
KPI generation
Visualization development

📊 Dashboard Filters

The dashboard provides interactive filters for:

City
Cuisine Type
Payment Mode

These filters allow dynamic business analysis.   

# 
