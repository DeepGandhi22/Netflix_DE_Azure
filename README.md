# Azure Data Engineering Project

## Goal
The main goal of this project is to familiarize myself with the different functions and services of Microsoft Azure used for Data Engineering tasks.


## Project Architecture
![Data Architecture](https://github.com/user-attachments/assets/37a60ec2-6d16-4241-b59a-22360a31b22c)

The above diagram illustrates the pipeline I created to complete this project.  
Since the data was not very complex, only two containers were created: **Bronze** and **Silver**.

---

## Pipeline Overview

### 1. Data Ingestion - Azure Data Factory
Azure Data Factory was used to ingest data from GitHub into the **Bronze** container, which holds raw data files.

![Data Factory](https://github.com/user-attachments/assets/9e98722a-d4a5-432c-a5a7-eb7147900aa3)

---

### 2. Data Transformation - Azure Databricks
Azure Databricks (using PySpark) was utilized to transform the data. The processed data was stored in the **Silver** container.

![Databricks](https://github.com/user-attachments/assets/03dcd316-ab5d-4744-a19d-d9503da8f1f2)

---

### 3. Data Analysis - Azure Synapse Analytics
Finally, Azure Synapse Analytics was used to further analyze the data and leverage its powerful functionalities.

![Synapse Analytics](https://github.com/user-attachments/assets/fefa24af-6fb0-406b-9cfe-008a81695585)
![Synapse Chart](https://github.com/user-attachments/assets/49d78b2c-9f4c-4aea-9278-6cc99c13a92d)

---

## Technologies Used
- **Microsoft Azure**
  - Azure Data Factory
  - Azure Blob Storage (Bronze and Silver Containers)
  - Azure Databricks (PySpark)
  - Azure Synapse Analytics
- **GitHub** (for data source)
- **PySpark** (for data transformation)

---

## Learnings
Through this project, I gained hands-on experience with various Azure services, learned how to build an end-to-end data pipeline, and understood the basics of modern data engineering workflows.

---
