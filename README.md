# RWD_Medallion_Pipeline.ipynb
Real World Data Medallion Pipeline
# Real-World Data (RWD) Medallion Lakehouse Pipeline

This repository contains a complete PySpark implementation of a **Databricks Medallion Architecture** designed to process raw Electronic Health Records (EHR) into clinical business analytics.

## 🚀 Key Features
- **Bronze Layer:** Raw JSON EHR payload ingestion with ingestion metadata tracking.
- **Silver Layer:** Schema enforcement, data deduplication, and standardization of ICD-10 codes to **OMOP CDM Concept IDs**.
- **Gold Layer:** Population health aggregations computing 30-day readmission counts and percentage rates.
- **Documentation:** Complete line-by-line technical explanations included directly within the notebook markdown cells.

## 📁 Files in this Repository
- `RWD_Medallion_Pipeline.ipynb` - Interactive PySpark Jupyter Notebook containing all pipeline code and detailed step-by-step documentation.

## 🛠️ Tech Stack
- **Databricks / PySpark**
- **Delta Lake**
- **OMOP Common Data Model (CDM)**
