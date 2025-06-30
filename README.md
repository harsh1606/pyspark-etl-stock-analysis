# 🚀 Cloud-based ETL Pipeline with PySpark and MySQL

## 📌 Overview

This project implements a scalable cloud data pipeline using **PySpark** to process, clean, and transform large datasets and store the processed results in a **MySQL database**. It showcases an end-to-end ETL (Extract, Transform, Load) architecture ideal for modern data engineering workflows.

---

## 🔧 Technologies Used

- **Apache Spark (PySpark)** — for distributed data processing
- **Python** — primary programming language
- **MySQL** — for storing the cleaned and transformed data
- **pandas** — for local data manipulation
- **Google Colab** — for cloud-based development and execution

---

## 🛠️ Project Workflow

### 1. **Data Extraction**
- Data is imported from structured CSV files.
- Spark DataFrames are used for handling large volumes efficiently.

### 2. **Data Transformation**
- Cleaning nulls, dropping duplicates, formatting date fields.
- Standardizing column names and ensuring schema consistency.
- Feature engineering and deriving metrics.
- Exploratory Data Analysis (EDA) using PySpark and pandas.

### 3. **Data Loading**
- Transformed data is loaded into a **MySQL database** using JDBC connectivity.
- All MySQL configurations are handled via the `db_config` module.

---

## 📊 Visualization
Post-ETL, trends and summaries are visualized using Matplotlib to identify:
- Sales distribution
- Category-wise performance
- Regional insights

---

## 🗃️ Folder Structure

```
Cloud_ETL_Project/
│
├── Cloud_Project_Final.ipynb      # Jupyter notebook with entire ETL pipeline
├── db_config.py                   # Contains MySQL DB connection details
├── README.md                      # Project documentation
```

---

## 🔐 Note
- Update your own MySQL credentials in `db_config.py`.
- Ensure that the target MySQL server is accessible and the required table exists or can be created.

---

## 👤 Author

**Harsh Kumar Tyagi**  
📫 [harshtyagi022@gmail.com](mailto:harshtyagi022@gmail.com)  
🔗 [GitHub: harsh1606](https://github.com/harsh1606)
