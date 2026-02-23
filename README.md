# Regional-Sales-Analysis-Dashboard-Excel-SQL-Power-BI

---

# Table of Contents

### <a href="#-project-overview">Overview</a>
### <a href="#-Key-Business-Problems-Addressed">Business Problems</a>
### <a href="#-Research-Questions">Research Questtins</a>
### <a href="#-data-preparation--exploratory-analysis-postgresql">Data cleaning & EDA</a>
### <a href="#-Key-Performance-Metrics">Key Metrics</a>
### <a href="#/Dataset/">Dataset</a>
### <a href="/Dashboard/Regional%20Sales%20Analysis%20Dahboard.pbix">Dashboard</a>
### <a href="#/Preview">Preview</a>
### <a href="#-Key-Insights">Key Insights</a>
### <a href="#-how-it-works">How it works</a>
### <a href="-why-this-project-stands-out">Why this project stands out</a>
### <a href="#-tools--skills-used">Tools & Skills used</a>
### <a href="-helping-feedback--recommendations">Helping & feedback recommendations</a>
### <a href="#created-by">Created by</a>

---

# 🔎 Project Overview

This project analyzes multi-year regional sales performance to uncover insights related to product profitability, customer segmentation, category efficiency, and seasonal revenue trends.

The objective is to transform raw transactional data into actionable business intelligence using a structured analytics workflow: data cleaning, exploratory analysis, and interactive dashboard development.


---

# 🎯 Key Business Problems Addressed

## 1️⃣ Product Profitability

High-cost bikes and frames require significant inventory investment. Management needs to evaluate whether these premium products generate proportional revenue and profit compared to lower-cost, high-volume accessories.

## 2️⃣ Customer Segmentation

Leadership lacks clarity on which age groups and geographic regions contribute the most to revenue, limiting the ability to execute targeted marketing strategies.

## 3️⃣ Category Efficiency

Revenue alone does not determine performance. Management requires a clear comparison of revenue versus profit margins across categories to identify the most efficient business segments.

## 4️⃣ Revenue & Seasonality Trends

Limited visibility into monthly and yearly sales patterns makes forecasting and planning unreliable.


---

# 🔬 Research Questions

- Which products drive the highest sales volume and revenue?


- Which customer segments (age group + region) generate the most revenue?


- Which product categories are most efficient in generating profit relative to revenue?


- What are the year-over-year and seasonal sales trends?




---

# 🧹 Data Preparation & Exploratory Analysis (PostgreSQL)

## Customers Dataset

- Identified and handled 300+ N/A values in the country field.

- Standardized 15 missing gender records as "Unknown".

- Identified 17 missing birthdates (retained for transparency).

- Derived customer age from birthdate.

- Calculated total customers, revenue per customer, and gender distribution.


## Products Dataset

- Assigned missing category labels where applicable.

- Filtered relevant columns for analysis.

- Calculate Total product count by category
, Average cost per Category distribution



## Sales Dataset

- Cleaned null order dates.

- Calculate Total revenue, Total quantity sold, Total orders, Top 5 products by sales,Sales distribution by country and Average selling price. 


---

# 📈 Key Performance Metrics

- Total Sales: $29.35M

- Total Quantity Sold: 60K

- Total Customers: 18K

- Total Profit: $11.68M

- Overall Profit Margin: 39.8%



---

# 💡 Key Insights

### 🥇 Top Performing Product

- Sport-100 Helmet (Red) generated the highest individual sales ($78K), primarily from the Accessories category.

### 👥 Customer Demographics

- The 40–49 age group is the strongest revenue-driving segment across genders.
The United States accounts for 41% (7,481 customers) of total customers, making it the dominant market.

### 📊 Year-over-Year Trends

- 2013 represents the strongest performing year, while 2010 was the weakest. Clear seasonal patterns are visible, supporting better forecasting.

### 📦 Category Efficiency

- Although Bikes generate higher revenue, the Accessories category demonstrates stronger profit efficiency, delivering over 10% higher relative profitability compared to other categories.


---

# ⚙️ How It Works

-  This project follows a structured analytics pipeline:

- Initial dataset validation and inspection in Excel.


- Data upload into PostgreSQL for cleaning and structured querying.


- Exploratory Data Analysis (EDA) using SQL for metric computation and segmentation.


- Processed datasets loaded into Power BI.


- Development of interactive dashboards with:
KPI cards,Demographic breakdowns, Category performance comparisons, Geographic distribution mapping and Time-series trend analysis

- Users can filter by:

- Year

- Country

- Gender


### The dashboard dynamically updates metrics and visualizations to support real-time analytical exploration.


---

# 🚀 Why This Project Stands Out

## 1️⃣ End-to-End Analytics Workflow

This is not just a dashboard project. It demonstrates:

- Data cleaning in SQL

- Structured EDA

- Metric engineering

- Business framing

- Visualization and storytelling


## 2️⃣ Business-Driven Problem Framing

Instead of building visuals first, this project begins with clearly defined business problems and research questions, aligning analysis with decision-making needs.

## 3️⃣ Profitability Focus (Not Just Revenue Reporting)

Many sales dashboards focus solely on revenue. This project incorporates:

Profit margin comparison

Category efficiency analysis

Cost-awareness in decision-making


## 4️⃣ Multi-Dimensional Segmentation

Analysis includes:

- Product-level insights

- Category-level profitability

- Age-group segmentation

- Regional performance

- Time-series trends


- ➡️ This reflects real-world analytical depth beyond surface-level reporting.


---

# 🛠 Tools & Skills Used

## Tools

- Microsoft Excel

- PostgreSQL

- Power BI


## Skills Demonstrated

- Exploratory Data Analysis (EDA)

- Data Cleaning & Transformation

- SQL Query Optimization

- Business Problem Structuring

- KPI Development

- Interactive Dashboard Design

- Data Storytelling

- Analytical & Critical Thinking

---

# 💬 Helping Feedback & Recommendations


- Your Feedback & Critics means a lot to me . feel free to collaborate & giving feedback or asking questions on this project. I really appreciate every critic & great idea , feel free to reach out .

---

# Created By
- 🙋‍♂️ Tarun Rajora
- 📞 +91 8218-228575 
- 📧 <a href="mailto:trajora106@gnmail.com">trajora106@gmail.com</a>
- 🔗 <a href="https://www.linkedin.com/in/tarun-rajora-1531332a1/">Linkedin</a>

