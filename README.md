# 🗄️ Databases, SQL & Cloud Analytics Foundations

![SQL](https://img.shields.io/badge/SQL-003B57?style=for-the-badge&logo=postgresql&logoColor=white)
![Microsoft Azure](https://img.shields.io/badge/Microsoft_Azure-0078D4?style=for-the-badge&logo=microsoft-azure&logoColor=white)
![Microsoft Fabric](https://img.shields.io/badge/Microsoft_Fabric-0078D4?style=for-the-badge&logo=microsoft&logoColor=white)
![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=power-bi&logoColor=black)

---

## 📌 Overview
This repository showcases **core database concepts, SQL analytics, and cloud data platform fundamentals**, aligned to **Data Analyst, BI Analyst, and Junior Data Engineer** roles. It demonstrates how **raw, high-volume data** is transformed into **structured, insight-ready datasets** using **Microsoft Fabric and Azure**.

## ☁️ Cloud & Analytics Platform Context
- **Microsoft Azure**: scalable data storage and analytics services
- **Microsoft Fabric**: unified platform combining Lakehouse, Warehouse, and BI
- Relational models built on top of raw, non-relational data sources
- SQL outputs designed for downstream **Power BI dashboards**

---

## 🧠 Relational & Non-Relational Data Concepts

### Relational Databases
- Structured, schema-based tables with enforced relationships
- Primary and foreign keys to maintain data integrity
- Optimised for reporting and analytical queries  
**Examples:** Azure SQL Database
  
<img width="517" height="226" alt="Picture1" src="https://github.com/user-attachments/assets/8ba81ef1-653c-4241-8d39-b2ade179a2b8" />

### Non-Relational & Semi-Structured Data
- Flexible or evolving schemas
- Designed for large-scale, event-driven datasets
- Supports real-time ingestion and scalability

<img width="669" height="487" alt="Picture5" src="https://github.com/user-attachments/assets/0d72338e-7ccc-435b-b0b4-9055ee836fb1" />

**Fabric Use Case:**  
Taxi journey data (e.g. pickup/drop-off times, locations, fares, trip distances), where records arrive at scale, vary over time, and are better ingested in a **lakehouse-style architecture** before modelling.

---

## 🚕 Microsoft Fabric — Taxi Dataset Exercises
Using a **Taxi database** in **Microsoft Fabric**, I worked with **high-volume, semi-structured transport data** to understand how modern analytics platforms handle real-world ingestion and transformation.


### Key Focus Areas
- Ingesting raw taxi trip data into a **Fabric Lakehouse**
- Handling large datasets without rigid upfront schemas
- Transforming non-relational data into **structured tables**
- Preparing data for **SQL analytics and Power BI reporting**

<img width="665" height="537" alt="Picture7" src="https://github.com/user-attachments/assets/7d2783a3-b0f4-4905-bb99-2491645c10b8" />

<img width="803" height="396" alt="Picture6" src="https://github.com/user-attachments/assets/816fcae6-7db6-49be-8434-5acce10a7ff7" />

This mirrors enterprise data pipelines where **event-based data** is landed first, then refined for analytics.

---
