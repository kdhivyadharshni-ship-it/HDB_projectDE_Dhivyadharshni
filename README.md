#  HDB Data Engineering Project (Singapore)

## Overview
This project demonstrates an end-to-end data engineering pipeline using publicly available datasets from data.gov.sg.

The goal is to ingest, process, and analyze HDB resale data to generate insights, while designing a scalable and secure AWS-based architecture.

---

##  Architecture Summary
The solution is designed using AWS services:

- Data Source: data.gov.sg (Public API)
- Ingestion: AWS Glue (Batch Processing)
- Storage: Amazon S3 (Raw & Processed Zones)
- Processing: AWS Glue (ETL)
- Metadata: AWS Glue Data Catalog
- Query Engine: Amazon Athena
- Visualization: Tableau

---

## Data Pipeline Workflow

1. Extract data from data.gov.sg (batch ingestion)
2. Store raw data in S3 (Raw Zone)
3. Clean and transform data using ETL
4. Store processed data in S3 (Processed Zone)
5. Query data using Athena
6. Visualize insights using Tableau

---

## Dataset
- Source: data.gov.sg
- Example: HDB resale price dataset
- Format: CSV / JSON

---

##  How to Run the Project

### 1. Clone Repository
```bash
git clone https://github.com/kdhivyadharshni-ship-it/HDB_projectDE_Dhivyadharshni.git
cd HDB_projectDE_Dhivyadharshni
