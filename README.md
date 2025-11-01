# customer_data_analysis
Data Analytics Projects showcasing customer behaviour using Python , SQL  and Looker Studio
# 📊 Data Analytics Project

## 🔍 Overview

This project demonstrates a complete **data analytics workflow**, starting from **data loading and cleaning** to **exploratory data analysis (EDA)**, **SQL querying**, and **dashboard visualization**.
The goal is to extract insights from raw data using **Python**, **PostgreSQL**, and **Looker Studio**, following best practices in data preparation and analysis.

---

## 🗂️ Dataset

* **Source:** Public dataset (CSV format)
* **Description:** The dataset contains records related to [insert domain, e.g., customer transactions, product sales, or HR data].
* **Key Columns:**

  * `customer_id` / `product_id`
  * `purchase_amount` / `date`
  * `gender` / `category`
  * `rating` / `region`
* **Size:** Approximately [mention number of rows] records.

---

## 🧰 Tools & Technologies

* **Python (Pandas, NumPy, Matplotlib, Seaborn)** – for data cleaning and EDA
* **PostgreSQL** – for executing SQL queries and relational data analysis
* **Looker Studio (Google Data Studio)** – for interactive dashboard creation
* **Jupyter Notebook / VS Code** – for scripting and workflow execution

---

## ⚙️ Steps Followed

### 1. Data Loading

* Imported the dataset using **Pandas**.
* Verified column types and handled missing or inconsistent values.

### 2. Data Cleaning

* Removed duplicates, nulls, and irrelevant columns.
* Standardized date formats, categorical values, and numerical ranges.

### 3. Exploratory Data Analysis (EDA)

* Generated descriptive statistics (mean, median, mode).
* Visualized relationships using bar charts, histograms, and correlation heatmaps.
* Identified trends and anomalies in key metrics.

### 4. SQL Querying (PostgreSQL)

* Loaded the cleaned dataset into a **Postgres server**.
* Executed SQL queries such as:

  * Total revenue by gender or region
  * Top 5 products by average rating
  * Monthly sales trends and purchase frequency

### 5. Dashboard Development (Looker Studio)

* Connected the SQL data source to Looker Studio.
* Built a visual dashboard highlighting:

  * Sales and revenue performance
  * Product category analysis
  * Customer segmentation insights
  * Time-based trend analysis

---

## 📈 Dashboard Results

The final **Looker Studio dashboard** presents:

* Real-time KPIs such as total sales, average revenue per customer, and top products.
* Visual breakdowns using bar charts, pie charts, and time-series graphs.
* Interactive filters for region, category, and date range.

> [Include your dashboard link here, e.g.: **View Dashboard** → *(insert Looker Studio link)*]

---

## 🚀 How to Run the Project

### 1. Clone Repository

```bash
git clone https://github.com/yourusername/data-analytics-project.git
cd data-analytics-project
```

### 2. Install Dependencies

```bash
pip install -r requirements.txt
```

### 3. Run Python Script or Notebook

```bash
python data_analysis.py
# or
jupyter notebook data_analysis.ipynb
```

### 4. Set Up PostgreSQL

* Create a database and table.
* Import the cleaned CSV into Postgres.
* Run SQL queries from `queries.sql`.

### 5. Visualize in Looker Studio

* Connect to your PostgreSQL dataset.
* Import the visuals and filters used in the shared dashboard.

---

## 📬 Contact

**Author:** Abhijit Sarkar
**Role:** Data Analyst / Data Science Intern


---

**End Goal:** Deliver actionable insights through data cleaning, SQL querying, and visual storytelling.
