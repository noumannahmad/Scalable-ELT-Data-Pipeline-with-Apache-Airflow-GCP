# Scalable ELT Data Pipeline with Apache Airflow & GCP

This project demonstrates how to build a robust **ELT (Extract, Load, Transform)** data pipeline using **Google Cloud Platform (GCP)** and **Apache Airflow** to process **1 million+ records**. The pipeline automates the extraction of CSV files from Google Cloud Storage (GCS), loads the raw data into BigQuery, and transforms it to generate country-specific tables and reporting views optimized for business analytics.


---

## 🚀 Features

- Extracts CSV data files from Google Cloud Storage.
- Loads raw data into a staging table in BigQuery.
- Transforms data into country-specific datasets and views.
- Utilizes Apache Airflow for workflow orchestration.
- Outputs clean, structured, and analysis-ready datasets.
- Enables dynamic reporting via Looker Studio.

---

## 🏗️ Architecture Overview

![Pipeline Architecture](https://github.com/user-attachments/assets/87cdc79c-c9a1-4c4d-887a-ab6007394bc7)

---

## 🔄 Workflow Steps

1. **Extract**
   - Check for new CSV files in a specified GCS bucket.
2. **Load**
   - Ingest raw data into a BigQuery staging table.
3. **Transform**
   - Create country-level tables from the staging layer.
   - Generate reporting views for business insights.

### 🔍 Data Layers

- **Staging Layer**: Raw unprocessed data from GCS.
- **Transform Layer**: Cleaned and structured tables.
- **Reporting Layer**: Aggregated and filtered views for dashboarding.

---

## 🧰 Requirements

### Tools and Cloud Services

- **Google Cloud Platform (GCP)**
  - Cloud Storage
  - BigQuery
  - Compute Engine (to host Airflow)
- **Apache Airflow**
  - With Google Cloud provider integrations

---

## ⚙️ Setup Instructions

### Prerequisites

1. Active GCP project with:
   - Enabled APIs: BigQuery, Cloud Storage
   - Service Account with appropriate permissions
2. Apache Airflow (recommended via VM or Docker)

---

## ✅ Final Output

### 📊 Airflow DAG

![Airflow DAG](https://github.com/user-attachments/assets/8e8b8373-9d2a-417b-9fd9-5f42171c06f8)

### 📈 Looker Studio Report

![Looker Report](https://github.com/user-attachments/assets/d06f0d3e-a1d0-404a-9eb7-c61c85df8257)

---

## 📬 Contact

For questions or feedback, feel free to reach out via GitHub Issues or connect on LinkedIn.
