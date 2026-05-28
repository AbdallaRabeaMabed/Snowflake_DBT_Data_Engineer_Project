# 🏠 Airbnb End-to-End Data Engineering Project

## 📌 Overview
This project implements a complete **end-to-end data engineering pipeline** for Airbnb data using modern cloud technologies.  
The solution demonstrates best practices in **data warehousing, transformation, and analytics** with:

- **Snowflake** (cloud data warehouse)  
- **dbt (Data Build Tool)** for transformations  
- **AWS (S3)** for cloud infrastructure  

---

## ⚙️ Pipeline Architecture
The pipeline processes **Airbnb listings, bookings, and hosts data** through a **Medallion Architecture**:

- **Bronze Layer** → Raw ingestion of source data  
- **Silver Layer** → Cleaned and standardized datasets  
- **Gold Layer** → Analytics-ready tables for BI and reporting  

---

## 🔑 Key Features
- **Incremental loading** for efficiency  
- **Slowly Changing Dimensions (SCD Type 2)** to track historical changes  
- **Analytics-ready datasets** for dashboards and insights  

---

## 🎯 Purpose
This project showcases how to design a **scalable, cloud-native data engineering workflow** that supports real-world analytics use cases for Airbnb data.
