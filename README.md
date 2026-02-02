# Customer_Behavior_Analysis
Data Analytics project showcasing customer behavior analysis using python, sql and power bi


## Overview

This project analyzes customer purchase behavior using Python, SQL, and Power BI. The workflow includes loading and cleaning data, performing exploratory data analysis (EDA), running SQL queries on PostgreSQL/SQL Server, and building an interactive Power BI dashboard. The final outcome is a comprehensive report highlighting insights and actionable trends in customer purchases.

---

## Dataset

* The dataset contains customer purchase records, including fields such as:

  * `customer_id`
  * `category`
  * `item_purchased`
  * `purchase_date`
  * `quantity`
  * `amount_spent`
* The data is used to understand purchasing trends, top products, and category-wise analysis.

---

## Tools & Technologies

* **Python** – pandas, numpy, matplotlib, seaborn
* **SQL** – PostgreSQL / SQL Server for querying and aggregating data
* **Power BI** – for building interactive dashboards and visualizations
* **Jupyter Notebook / VS Code** – for Python development and EDA
* **GitHub** – version control

---

## Steps Performed

1. **Data Loading** – Imported CSV/Excel dataset into Python using pandas.
2. **Data Cleaning** – Handled missing values, corrected data types, and ensured consistency.
3. **Exploratory Data Analysis (EDA)** – Identified trends, patterns, and anomalies through summary statistics and visualizations.
4. **SQL Queries** – Loaded data into PostgreSQL/SQL Server and performed queries such as:

   * Category-wise purchase counts
   * Top N items per category
   * Revenue trends over time
5. **Power BI Dashboard** – Created interactive dashboards showing:

   * Total purchases and revenue per category
   * Top-selling products
   * Customer purchase trends
6. **Report Generation** – Summarized findings, insights, and recommendations in a final report.

---

## Dashboard

The Power BI dashboard includes:

* **Category Analysis:** Total orders and revenue by product category.
* **Top Products:** Highlighting top 3 items per category.
* **Trend Analysis:** Visualizations of sales trends over time.
* **Interactive Filters:** Slicers for category, date, and region.

---

## Results & Insights

* Identified top-selling products per category.
* Discovered seasonal trends in customer purchases.
* Highlighted underperforming products for potential marketing focus.
* Generated actionable insights for business decision-making.

---

## How to Run the Project

1. Clone the repository:

```bash
git clone <https://github.com/dhruvdhandukiya/Customer_Behavior_Analysis.git>
```

2. Open the Jupyter Notebook (`.ipynb`) or Python scripts to run data loading, cleaning, and EDA.
3. Connect to your PostgreSQL/SQL Server database and run the SQL queries provided.
4. Load the processed dataset into Power BI Service/Desktop to view the dashboard.
5. Review the final report for insights and recommendations.

---

**Note:** Ensure you have the required Python libraries installed (`pandas`, `numpy`, `sqlalchemy`, `psycopg2`) and access to a PostgreSQL/SQL Server instance to run queries.


