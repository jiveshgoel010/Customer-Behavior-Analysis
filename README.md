# Customer Behavior Analysis

An end-to-end data analytics project exploring customer shopping behavior using Python, SQL, and Power BI. The project transforms raw customer data into actionable insights through data cleaning, exploratory analysis, SQL queries, and interactive visualization.

## Overview

The goal of this project is to understand customer purchasing patterns, identify shopping trends, and explore factors influencing buying behavior.

The project demonstrates a complete data analytics workflow, from loading and preparing a dataset to building a dashboard and presenting findings in a report.

## Dataset

The project uses a customer shopping behavior dataset containing information about customer demographics, purchasing habits, product categories, and shopping preferences.

The dataset is included in this repository:

- `customer_shopping_behavior.csv`

## Tools & Technologies

| Tool | Purpose |
|---|---|
| Python | Data loading, cleaning, and EDA |
| Pandas & NumPy | Data manipulation and analysis |
| Jupyter Notebook | Analysis and documentation |
| SQL | Data querying and business analysis |
| PostgreSQL / MySQL / SQL Server | Relational database management |
| Power BI | Interactive dashboard and visualization |

## Project Workflow

### 1. Data Loading & Exploration

- Loaded the dataset into Python using Pandas.
- Examined the dataset structure, data types, and summary statistics.
- Identified missing values, duplicates, and potential data quality issues.

### 2. Data Cleaning & EDA

- Cleaned and prepared the dataset for analysis.
- Handled missing values and duplicate records where necessary.
- Explored customer demographics, purchasing patterns, and product preferences.
- Identified trends and relationships through exploratory data analysis.

### 3. SQL Analysis

- Imported the cleaned dataset into a relational database.
- Used SQL queries to analyze customer behavior and purchasing trends.
- Applied aggregations, filtering, grouping, and window functions to answer business questions.

### 4. Power BI Dashboard

- Connected the analyzed data to Power BI.
- Created interactive visualizations to present key findings.
- Designed charts and summary metrics to make customer behavior easier to understand.

### 5. Reporting

- Documented the analytical process and findings.
- Summarized key observations and business insights in a project report.

## Dashboard

The Power BI dashboard provides a visual overview of customer shopping behavior, purchasing patterns, and product preferences.

**Dashboard file:** `customer_behavior_dashboard.pbix`

The interactive dashboard can be opened using Microsoft Power BI Desktop.

## Results & Key Learnings

The project provides a structured view of customer purchasing behavior and demonstrates how data analytics can support business decision-making.

Key takeaways include:

- Identifying purchasing patterns across customer segments.
- Understanding product preferences and shopping trends.
- Using SQL to answer business-related questions efficiently.
- Translating analytical findings into clear, interactive visualizations.
- Developing an end-to-end workflow for a real-world data analytics project.

## Repository Structure

```text
Customer-Behavior-Analysis/
│
├── customer_shopping_behavior.csv
├── customer_shopping_behavior_analysis.ipynb
├── sql_queries.sql
├── customer_behavior_dashboard.pbix
├── Customer Shopping Behavior Analysis.pdf
├── Problem Statement.pdf
└── README.md
```

## How to Run

### Prerequisites

- Python 3.x
- Jupyter Notebook
- PostgreSQL, MySQL, or SQL Server
- Microsoft Power BI Desktop

### Setup & Execution

1. Clone the repository:

   ```bash
   git clone https://github.com/jiveshgoel010/Customer-Behavior-Analysis.git
   ```

2. Navigate to the project directory:

   ```bash
   cd Customer-Behavior-Analysis
   ```

3. Install the required Python libraries:

   ```bash
   pip install pandas numpy matplotlib seaborn sqlalchemy jupyter
   ```

4. Launch Jupyter Notebook:

   ```bash
   jupyter notebook
   ```

5. Open `customer_shopping_behavior_analysis.ipynb` and run the cells to explore the dataset, perform data cleaning, and conduct EDA.

6. Import the dataset into your preferred SQL database and execute the queries in `sql_queries.sql`.

7. Open `customer_behavior_dashboard.pbix` in Power BI Desktop to explore the interactive dashboard.

**Note:** Database connection settings may need to be configured based on your local SQL environment.

## Project Files

- [Python Analysis Notebook](customer_shopping_behavior_analysis.ipynb)
- [SQL Queries](sql_queries.sql)
- [Power BI Dashboard](customer_behavior_dashboard.pbix)
- [Project Report](Customer%20Shopping%20Behavior%20Analysis.pdf)
- [Problem Statement](Problem%20Statement.pdf)
