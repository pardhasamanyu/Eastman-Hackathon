# Eastman Hackathon — Manufacturing & Supply Chain Analytics

## Project Overview

This project analyzes manufacturing, sales, inventory, production quality, and delivery data to identify business-critical trends and operational risks.

Using Python, Pandas, and SQL, the project aims to answer five key business questions and generate actionable insights to support better decision-making.

## Business Questions

### 1. Top 10 Products by Revenue
Which products generated the highest revenue during the available period?

**Objective:** Rank the top 10 products by total revenue and identify the strongest revenue contributors.

### 2. Regional Sales Performance
Which regions show the strongest and weakest sales performance?

**Objective:** Compare sales performance across regions to identify high-performing and underperforming markets.

### 3. Inventory Risk Analysis
Which products experienced excess inventory (Cap ≥ 1,500) and stockout risk (Cap ≤ 50) during the available period?

**Objective:**
- Identify affected products, plants, and months.
- Highlight products with repeated stockout-risk occurrences.
- Distinguish excess inventory from potential stock shortages.

### 4. Production Rejection Rate
What is the production rejection rate for each product within each plant?

**Objective:** Calculate rejection rates at the product-and-plant level to identify quality issues and production areas requiring improvement.

### 5. Customers with the Most Delayed Deliveries
Identify the top 5 customers with the highest number of delayed deliveries.

**Objective:** Rank customers by delayed delivery count to identify recurring delivery service issues.

## Tools & Technologies

- **Python** — Data analysis and processing
- **Pandas** — Data cleaning and transformation
- **Jupyter Notebook** — Exploratory analysis
- **SQL** — Business queries and aggregations
- **Git & GitHub** — Version control

## Project Workflow

1. **Data Understanding:** Inspect datasets, columns, data types, and relationships.
2. **Data Cleaning:** Validate data types, handle missing values, and check duplicates.
3. **Exploratory Analysis:** Understand the structure and quality of the available data.
4. **SQL Analysis:** Answer the five business questions using appropriate joins, aggregations, filters, and grouping.
5. **Insight Generation:** Interpret the results and identify meaningful business patterns.
6. **Recommendations:** Suggest improvements supported by the analytical findings.

## Repository Contents

- `raw-prod.ipynb` — Production data analysis.
- `cleaned-delivery.ipynb` — Delivery data cleaning and analysis.
- `Source Files/` — Source datasets.

*Update the repository contents if filenames or folder structures change.*

## Project Status

In progress — Data preparation and business analysis.

production-table-
has no null values, no duplicate rows, 1 negative produced quantity
rejection rate
production varience 
achievement %
accepted quantity

plants-
total planned, total produced, total rejected, production runs, achievement rate, rejection rate
which plant produces highest, met production target, has highest rejection rate

monthly analysis-
planned- produced and rejected


delivery table-
converted date columns to date time (str to datetime)
no null duplicate values
delay days - how many no delay days, 1 day days etc
insights- delayed, ontime, delay rate, average delay days

GitHub: [@pardhasamanyu](https://github.com/pardhasamanyu)

---

*Developed as part of the Eastman Hackathon.*
