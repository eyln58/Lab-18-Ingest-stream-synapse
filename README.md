# 🚀 Real-Time Streaming Ingestion & Aggregation with Azure Stream Analytics

## Overview

This project demonstrates the end-to-end architecture for **streaming data ingestion** and **real-time analytics** using **Azure Stream Analytics**, **Azure Event Hubs**, **Synapse Dedicated SQL Pools**, and **Azure Data Lake Storage Gen2**.

From ingestion to aggregation, I built a complete pipeline capable of both real-time operational insights and batch-like summarized outputs.

## 🧠 What I Did

- Provisioned all necessary Azure resources using **ARM templates and PowerShell** — including Synapse workspace, Event Hubs, SQL pools, and Storage.
- Built and tested a **streaming pipeline** that:
  - Ingests real-time order data from **Event Hubs** directly into a **Synapse SQL table**
  - Aggregates product order volumes over tumbling time windows (5 seconds)
  - Writes the summarized results as **CSV files to Azure Data Lake**
- Configured **multiple Stream Analytics jobs** to handle ingestion and aggregation separately
- Used **Synapse SQL** to validate data flow at each step from raw stream to structured lake output

## 🔍 What I Learned

- How to build scalable, event-driven pipelines using **Azure-native tools** with no external services
- Practical application of **Stream Analytics queries** with tumbling windows for time-based aggregation
- Experience with ingesting data into both **SQL pools** and **blob storage** simultaneously
- How to validate and query data across **structured (SQL)** and **semi-structured (CSV)** formats

## ⚙️ Tech Stack

- Azure Synapse Analytics (Dedicated SQL Pools)
- Azure Event Hubs
- Azure Stream Analytics
- Azure Data Lake Storage Gen2
- PowerShell & ARM Templates
- SQL & Stream Analytics Query Language

---

🔗 **Let’s connect and talk data engineering! Reach me on [LinkedIn](https://www.linkedin.com/in/eyilan/)**  
