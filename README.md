# 🔄 Customer Churn Prediction

> An end-to-end **Customer Churn Prediction** analytics pipeline — from raw CSV data to an interactive Power BI dashboard — built with **Python**, **SQL Server**, and **Power BI** to identify at-risk customers and drive retention strategies.

***

## 🏗️ Project Architecture

The project follows a 5-stage pipeline — from raw data ingestion through Python EDA, SQL analysis, and finally a Power BI dashboard.



| Stage | Tool | Description |
|-------|------|-------------|
| 1️⃣ **Data Source** | CSV File | Raw customer data from a local/external system |
| 2️⃣ **EDA & Modeling** | Python (Jupyter) | Data cleaning, exploration, feature engineering |
| 3️⃣ **Data Analysis** | SQL Server | Transformations, aggregations, business logic |
| 4️⃣ **Dashboard** | Power BI | Interactive KPI dashboard with visuals & slicers |
| 5️⃣ **Version Control** | GitHub | Source code, documentation & project tracking |

***

## 📖 Project Overview

Customer churn is one of the most critical challenges for subscription-based and retail businesses — retaining an existing customer is far less expensive than acquiring a new one. This project builds a complete analytics pipeline to identify customers at risk of churning and surface actionable insights.

**What's built:**

- End-to-end data pipeline from raw CSV to business insights
- Python-based EDA with data cleaning and feature engineering
- SQL Server scripts for deep-dive analysis and aggregations
- Interactive Power BI dashboard with filters by gender, category, subscription, and shipping

***

## 📊 Power BI Dashboard

The final deliverable is an interactive Power BI dashboard surfacing key churn insights across customer segments, product categories, and age groups.



**Key KPIs on the dashboard:**

- **3.9K** total customers
- **$59.76** average purchase amount
- **3.75** average review rating
- **27%** subscribers vs **73%** non-subscribers
- Revenue & Sales by category — Clothing, Accessories, Footwear, Outerwear
- Revenue & Sales by age group — Young Adult, Middle-aged, Adult, Senior

***

## 📂 Repository Structure

```
customer_churn_prediction/
│
├── dataset/                        # Raw CSV data file(s)
│
├── docs/                           # Project documentation & images
│   ├── architechture.png           # Project architecture diagram
│   └── Customer_churn_prediction.png  # Power BI dashboard screenshot
│
├── scripts/
│   ├── eda_notebook.ipynb          # Jupyter Notebook — EDA & Data Modeling
│   └── analysis.sql                # SQL Server scripts — Data Analysis & Cleaning
│
└── README.md
```

***

## 🛠️ Tools & Technologies

| Tool | Purpose |
|------|---------|
| **Python** (Jupyter Notebook) | EDA, Data Cleaning, Feature Engineering, Data Modeling |
| **SQL Server / SSMS** | Data loading, transformation, aggregations, business logic |
| **Power BI Desktop** | Interactive dashboard, DAX measures, KPIs & visuals |
| **Git / GitHub** | Version control, documentation, project tracking |

***

## 🚀 How to Run

1. **Clone the repo**
   ```bash
   git clone https://github.com/ChanakyaSreeHarshaG/customer_chrun_prediction.git
   ```

2. **Install Python dependencies**
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn jupyter
   ```

3. **Run the EDA Notebook**
   ```bash
   jupyter notebook scripts/eda_notebook.ipynb
   ```

4. **Set up SQL Server** — Open SSMS, create a new database, and run the SQL scripts from `scripts/` to load and analyze the data

5. **Open Power BI Dashboard** — Open the `.pbix` file in Power BI Desktop, update the SQL Server connection string to your local instance, and refresh the data

***

## 📊 Key Insights

- **73%** of customers do not hold a subscription — the largest churn-risk segment
- **Clothing** generates the highest revenue and sales volume across all categories
- **Young Adults and Middle-aged** customers drive the most revenue across age groups
- **Seniors** show comparatively lower purchase volumes — an opportunity for targeted retention
- Average purchase of **$59.76** and review rating of **3.75/5** provide customer satisfaction benchmarks

***

## 🛡️ License

This project is licensed under the [MIT License](LICENSE).

***

## 🙋 About Me

Hi, I'm **Chanakya Sree Harsha G** — a data enthusiast passionate about building end-to-end analytics solutions that turn raw data into real business insights.

Feel free to connect with me on [LinkedIn](https://www.linkedin.com/in/chanakyasreeharsha) or explore more of my work on [GitHub](https://github.com/ChanakyaSreeHarshaG).
