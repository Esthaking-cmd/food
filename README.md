# 🍽 Food Delivery Analytics Dashboard

## 📌 Project Overview

The **Food Delivery Analytics Dashboard** is a complete end-to-end **Data Analytics & Business Intelligence project** developed to analyze food delivery operations and generate actionable business insights from raw order data.

This project demonstrates the full analytics pipeline — from **data cleaning and preprocessing** to **database integration and interactive dashboard development** — enabling real-time analysis of customer behavior, revenue trends, restaurant performance, and delivery efficiency.

The final solution is an interactive **Streamlit dashboard** integrated with **MySQL**, allowing users to explore business metrics dynamically through filters and visualizations.

---

# 🎯 Project Objectives

The major objectives of this project are:

- Analyze customer ordering behavior
- Monitor revenue and profitability trends
- Evaluate delivery efficiency and operational performance
- Identify key reasons behind order cancellations
- Analyze restaurant and cuisine performance
- Build an interactive dashboard for business decision-making
- Create a scalable analytics workflow using Python and MySQL

---

# 🛠 Technologies Used

| Technology | Purpose |
|---|---|
| Python | Data analysis & dashboard development |
| Pandas | Data cleaning & transformation |
| NumPy | Numerical computations |
| Matplotlib | Data visualization |
| Plotly | Interactive visualizations |
| MySQL | Structured database storage |
| SQLAlchemy | Python-MySQL integration |
| PyMySQL | MySQL database connector |
| Streamlit | Interactive dashboard application |

---

# 📂 Project Structure

```bash
Food-Delivery-Analytics/
│
├── FOOD_ANALYSIS_PROJECT.ipynb
├── online_F_A.ipynb
├── app.py
├── README.md
```

---

# 📓 Project Files Description

## 1️⃣ FOOD_ANALYSIS_PROJECT.ipynb

This notebook contains the **initial level of data preprocessing and exploratory data analysis (EDA)**.

### Tasks Performed

- Data loading using Pandas
- Initial dataset exploration
- Missing value identification
- Invalid data handling
- Duplicate removal
- Data type conversion
- Basic Exploratory Data Analysis (EDA)

### Data Cleaning Techniques Used

```python
isnull()
fillna()
replace()
drop_duplicates()
astype()
to_datetime()
```

---

## 2️⃣ online_F_A.ipynb

This notebook focuses on **advanced preprocessing, feature engineering, and analytical data preparation**.

### Tasks Performed

- Advanced missing value handling
- Delivery time preprocessing
- Feature engineering
- Data transformation
- Analytical column generation
- Final dataset preparation

### Feature Engineering Techniques

- Weekend vs Weekday classification
- Distance binning
- Age group categorization
- Profit percentage calculation
- Delivery category generation

### Pandas Functions Used

```python
groupby()
transform()
apply()
cut()
value_counts()
median()
mean()
```

---

## 3️⃣ app.py

This file contains the complete **Streamlit Dashboard Application**.

### Main Functionalities

- Connects Python with MySQL using SQLAlchemy
- Loads cleaned data from MySQL database
- Performs dashboard-level preprocessing
- Generates interactive visualizations
- Displays business insights dynamically

---

# 🗄 Database Integration

The cleaned and transformed dataset is stored in a **MySQL database** for efficient data management and scalable querying.

## Database Features

- Structured table creation
- SQL-based data storage
- Python-MySQL integration
- Real-time dashboard querying

## Database Connection Example

```python
from sqlalchemy import create_engine

engine = create_engine(
    "mysql+pymysql://username:password@localhost/database_name"
)
```

---

# 📊 Dashboard Features

The Streamlit dashboard provides multiple analytical modules and KPI tracking systems.

## 📌 KPI Metrics

- Total Orders
- Total Revenue
- Average Order Value
- Average Delivery Time
- Cancellation Rate
- Average Delivery Rating

---

# 🔍 Analytical Insights

## 1️⃣ Customer & Order Analysis

- Top spending customers
- Age group vs order value analysis
- Weekend vs weekday ordering patterns

## 2️⃣ Revenue & Profit Analysis

- Monthly revenue trends
- Discount impact on profit margins
- High-revenue city analysis

## 3️⃣ Delivery Performance Analysis

- Average delivery time by city
- Distance vs delivery time analysis
- Delivery rating vs delivery time relationship

## 4️⃣ Restaurant Performance Analysis

- Top-rated restaurants
- Cancellation rate by restaurant
- Cuisine-wise performance analysis

## 5️⃣ Operational Insights

- Payment mode preferences
- Cancellation reason analysis
- Business operational trends

---

# 📈 Visualization Techniques Used

The project includes multiple data visualization techniques for better business understanding and interactive analysis.

### Visualizations Included

- Bar Charts
- Line Charts
- Scatter Plots
- Pie Charts
- Donut Charts
- Box Plots
- Violin Plots

Interactive charts are developed using **Plotly** for enhanced user experience and dynamic exploration.

---

# ⚙️ Data Preprocessing Workflow

## Step 1 — Raw Data Cleaning

- Missing value handling
- Invalid data correction
- Duplicate removal

## Step 2 — Feature Engineering

- Month extraction
- Distance categorization
- Age grouping
- Profit calculations

## Step 3 — Database Storage

- MySQL table creation
- Data import into MySQL
- SQLAlchemy integration

## Step 4 — Dashboard Development

- Streamlit dashboard creation
- Interactive filtering
- KPI generation
- Business visualization development

---

# 🎛 Dashboard Filters

The dashboard provides dynamic filtering options for:

- City
- Cuisine Type
- Payment Mode

These filters enable flexible and real-time business analysis.

---

# 🚀 Key Highlights

✔ End-to-End Data Analytics Project  
✔ Real-Time Interactive Dashboard  
✔ MySQL Database Integration  
✔ Business Intelligence & KPI Monitoring  
✔ Feature Engineering & Advanced Data Cleaning  
✔ Interactive Plotly Visualizations  
✔ Scalable Analytics Workflow  

---

# 📌 Future Enhancements

- Deployment using Streamlit Cloud / AWS
- Machine Learning-based sales prediction
- Real-time API integration
- Advanced customer segmentation
- Restaurant recommendation system

---

# 👨‍💻 Author

**Estha King**

Data Analytics & Data Science Enthusiast

