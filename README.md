# customer_chrun_prediction

## 🏗️ Project Architecture

The project follows a 5-stage pipeline:



| Stage | Tool | Description |
|-------|------|-------------|
| 1. Data Source | CSV File | Raw customer data from a local/external system |
| 2. EDA & Data Modeling | Python (Jupyter) | Import, clean, explore, feature engineer, and model the data |
| 3. Data Analysis | SQL Server | Load to SQL, transform, aggregate, apply business logic & advanced queries |
| 4. Dashboard | Power BI | Connect to SQL, build interactive dashboard with KPIs & visuals |
| 5. Version Control | GitHub | Source code, documentation, and project tracking |

***

## 📊 Power BI Dashboard

The final deliverable is an interactive Power BI dashboard that surfaces key churn insights across customer segments, categories, and age groups.



**Key KPIs visible on the dashboard:**
- **3.9K** total customers
- **$59.76** average purchase amount
- **3.75** average review rating
- **27%** subscribers vs **73%** non-subscribers
- Revenue & Sales breakdown by category (Clothing, Accessories, Footwear, Outerwear)
- Revenue & Sales breakdown by age group (Young Adult, Middle-aged, Adult, Senior)

***

## 📁 Repository Structure

```
customer_churn_prediction/
│
├── dataset/                  # Raw CSV data file(s)
│
├── docs/                     # Project documentation & images
│   ├── architechture-2.jpg   # Project architecture diagram
│   └── Customer_churn_prediction.jpg  # Power BI dashboard screenshot
│
├── scripts/                  # All project scripts
│   ├── eda_notebook.ipynb    # Jupyter Notebook — EDA & Data Modeling
│   └── analysis.sql          # SQL Server scripts — Data Cleaning & Analysis
│
└── README.md
```

***

## 🛠️ Tech Stack

| Tool | Purpose |
|------|---------|
| **Python** (Jupyter Notebook) | Exploratory Data Analysis, Data Cleaning, Feature Engineering, Data Modeling |
| **SQL Server** | Data loading, transformation, aggregations, business logic queries |
| **Power BI** | Interactive dashboard, DAX measures, KPIs, visuals |
| **GitHub** | Version control, documentation, project tracking |

***

## 🔍 Project Workflow

### 1. 📥 Data Source
- Format: CSV (Flat File)
- Source: Local / External System
- Contains customer demographics, purchase history, subscription status, shipping preferences, and review ratings

### 2. 🐍 EDA & Data Modeling (Python — Jupyter Notebook)
- Import CSV into a pandas DataFrame
- Handle missing values, outliers, and data type corrections
- Exploratory Data Analysis — distributions, correlations, segment analysis
- Feature Engineering — create new meaningful features for churn signals
- Data Modeling — prepare clean, model-ready dataset

**Output:** Cleaned / Model-Ready Data

### 3. 🗄️ Data Analysis in SQL Server
- Load cleaned data into SQL Server
- Data transformations and joins
- Aggregations by category, age group, and subscription status
- Business logic rules for churn classification
- Advanced queries for segmentation

**Output:** Analysis Results / Final Dataset

### 4. 📈 Power BI Dashboard
- Connect Power BI directly to SQL Server data
- Build data model with relationships
- Create DAX measures for KPIs
- Design interactive dashboard with slicers (Gender, Subscription Status, Shipping Method, Category)
- Visualize revenue, sales, and churn by segment

**Output:** Interactive Dashboard / Business Insights

### 5. 🐙 GitHub Repository
- Push all scripts, datasets, and documentation
- Version control for iterative development
- Full project documentation in README

***

## 🚀 Getting Started

### Prerequisites
- Python 3.8+
- Jupyter Notebook / JupyterLab
- Microsoft SQL Server (or SQL Server Express)
- Power BI Desktop (free)
- Git

### Installation & Setup

1. **Clone the repository**
   ```bash
   git clone https://github.com/ChanakyaSreeHarshaG/customer_chrun_prediction.git
   cd customer_chrun_prediction
   ```

2. **Install Python dependencies**
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn jupyter
   ```

3. **Run the EDA Notebook**
   ```bash
   jupyter notebook scripts/eda_notebook.ipynb
   ```

4. **Set up SQL Server**
   - Open SQL Server Management Studio (SSMS)
   - Run the SQL scripts from `scripts/` to create tables and load data

5. **Open Power BI Dashboard**
   - Open the `.pbix` file in Power BI Desktop
   - Update the SQL Server connection string to your local instance
   - Refresh the data

***

## 📌 Key Insights from the Analysis

- **73% of customers do not have a subscription**, representing the largest churn-risk segment
- **Clothing** generates the highest revenue and sales volume across all categories
- **Young Adults and Middle-aged** customers drive the most revenue across all age groups
- **Seniors** show comparatively lower sales volume, indicating an opportunity for targeted retention campaigns
- Average purchase amount of **$59.76** and review rating of **3.75/5** provide baseline benchmarks for customer satisfaction

***

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to:
- Fork this repository
- Create a new branch (`git checkout -b feature/your-feature`)
- Commit your changes (`git commit -m 'Add some feature'`)
- Push to the branch (`git push origin feature/your-feature`)
- Open a Pull Request

***

## 📬 Connect

**Chanakya Sree Harsha G**
- GitHub: [@ChanakyaSreeHarshaG](https://github.com/ChanakyaSreeHarshaG)

***

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

***

*Built with ❤️ using Python, SQL Server, Power BI, and GitHub*
