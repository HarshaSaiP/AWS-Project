# AWS Glue ETL Job for Data Cleansing

## 📌 Overview

This project uses **AWS Glue** to clean and standardize supplier data files and store the processed data in an **Amazon S3 data lake**.

### 🔄 Workflow

```text
Supplier Data
     ↓
   Amazon S3
     ↓
  AWS Glue ETL
     ↓
Clean & Standardize
     ↓
Amazon S3 Data Lake
```

## 🛠️ Technologies

* **AWS Glue** – ETL and data transformation
* **Amazon S3** – Data lake storage
* **Python / PySpark** – Data processing
* **Glue Data Catalog** – Schema management

## ✨ Features

* Remove duplicate records
* Handle missing values
* Standardize data formats
* Validate data types
* Store cleaned data in S3
* Handle changing source schemas

## 🎯 Goal

To build an automated ETL pipeline that converts **raw supplier data into clean, standardized data** ready for analysis and downstream applications.
