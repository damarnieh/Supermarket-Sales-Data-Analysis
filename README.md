# Supermarket Sales Data Analysis & Visualization

## Repository Outline

README.md – General documentation and explanation of the project

Supermarket_Sales_DAG.py – Airflow DAG for data extraction, cleaning, and loading

Supermarket_Sales_GX.ipynb – Notebook for data validation using Great Expectations

Supermarket_Sales_data_raw.csv – Raw dataset extracted from PostgreSQL

Supermarket_Sales_data_clean.csv – Cleaned dataset after the data processing stage

---

## Problem Background

Supermarkets generate large volumes of transaction data every day, including information about customers, products, and payment methods. Without proper data management and analysis, this data becomes difficult to utilize for business decision-making.

Therefore, a structured **data pipeline** is needed to efficiently manage the data, ensure data quality, and provide meaningful insights through data visualization.

---

## Project Output

* **Automated data pipeline** using Apache Airflow
* **Data quality validation** using Great Expectations
* **Visualization dashboard** in Kibana to analyze supermarket sales insights
* A dataset that has undergone extraction, cleaning, and validation processes

---

## Data

The dataset used in this project is **Supermarket Sales**, which contains supermarket transaction records.

Dataset information:

* Contains transaction details such as invoice ID, branch, customer type, product line, quantity, total sales, payment method, and rating
* Structured tabular data
* Used as the main data source for sales analysis and customer behavior insights

Data source: public supermarket sales dataset.

---

## Method

The methodology used in this project follows a **data engineering and data analytics pipeline**, including:

1. Extracting data from PostgreSQL
2. Validating data quality using Great Expectations
3. Cleaning and standardizing the data
4. Loading the processed data into Elasticsearch
5. Visualizing the data using Kibana

---

## Tech Stack

Tools and technologies used in this project include:

**Programming Language**

* Python

**Database**

* PostgreSQL

**Workflow Orchestration**

* Apache Airflow

**Data Validation**

* Great Expectations

**Search & Analytics Engine**

* Elasticsearch

**Visualization**

* Kibana

**Containerization**

* Docker & Docker Compose

**Python Libraries**

* pandas
* psycopg2
* elasticsearch

---

## References

Apache Airflow Documentation
https://airflow.apache.org/docs/

Great Expectations Documentation
https://greatexpectations.io/docs/

Elasticsearch & Kibana Documentation
https://www.elastic.co/guide/index.html

Supermarket Sales Dataset (Public Dataset)
https://github.com/vnaumq/supermarket_sales/blob/main/supermarket_sales.csv
