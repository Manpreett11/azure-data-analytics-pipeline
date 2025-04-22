# Azure Data Analytics Project

## 📊 Overview

This project demonstrates an end-to-end data analytics pipeline entirely built on Microsoft Azure. The solution uses Azure services like:

- **Azure Storage Account** for storing raw and processed datasets
- **Azure Data Factory** for orchestrating data pipelines
- **Azure Synapse Analytics** for data warehousing and querying
- **Azure Databricks** for data transformation and machine learning

## 🛠️ Services Used

- **Azure Blob Storage** –  Used for storing both raw and processed datasets
- **Azure Data Factory** – Used to orchestrate and automate end-to-end data pipelines
- **Azure Synapse Studio** – Used to query processed data and generate insights from customer datasets
- **Azure Databricks** – Used for data transformation, advanced analytics, and machine learning workflows

## 🔄 Pipeline Flow

1. Data is uploaded to Azure Storage via portal or logic apps.
2. Azure Data Factory triggers pipelines to move and transform data.
3. Transformed data is stored in Synapse tables.
4. Databricks is used for machine learning or complex transformations.

## 📸 Screenshots

Include:
- Data Factory pipeline:
  ![Image Alt](https://github.com/Manpreett11/azure-data-analytics-pipeline/blob/ca1d8aed29849ab4023b5cc14afd828190891478/DataFactoryPipeline.png.png)
- Databricks notebook :
  ![Image Alt](https://github.com/Manpreett11/azure-data-analytics-pipeline/blob/677b10fc5a9f9a1f16e92ea027ea383d68471c2f/DatabricksNotebook.png.png)
- Synapse query outputs:
  ![Image Alt](https://github.com/Manpreett11/azure-data-analytics-pipeline/blob/677b10fc5a9f9a1f16e92ea027ea383d68471c2f/StorageContainer.png.png)
- Storage containers:
 ![Image Alt](https://github.com/Manpreett11/azure-data-analytics-pipeline/blob/677b10fc5a9f9a1f16e92ea027ea383d68471c2f/SynapseQuery.png.png)

## 📂 Folder Structure (on Azure)

- `/data/raw/` – Raw uploaded datasets
- `/data/processed/` – Cleaned data
- `ADF Pipelines` – Configured in ADF Studio
- `Databricks Notebooks` – For data processing

## 🔐 Authentication

All services are authenticated using managed identities and integrated with Azure Active Directory.

## ✅ Outcome

The project successfully processed and analyzed data using scalable and serverless Azure services. The modular design allows easy enhancement and automation.

