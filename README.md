E-commerce Data Pipeline (Databricks)

Overview
Built an end-to-end data pipeline using **Medallion Architecture (Bronze, Silver, Gold)** to transform raw e-commerce data into analytics-ready datasets.

Tech Stack
* Databricks
* PySpark
* SQL
* Delta Lake

Pipeline
* **Bronze:** Raw data ingestion (orders, customers, products)
* **Silver:** Data cleaning, joins, transformations
* **Gold:** KPI aggregation for business insights

KPIs
* Total Revenue
* Sales by Category
* Top Customers
* Daily Sales Trend

Orchestration
dbutils.notebook.run("./bronze_notebook", 60)
dbutils.notebook.run("./silver_notebook", 60)
dbutils.notebook.run("./gold_notebook", 60)

Structure - 
notebooks/
 ├── bronze_notebook
 ├── silver_notebook
 ├── gold_notebook
 └── pipeline_notebook


Author
Shaik Nazma
