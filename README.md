# 🍞 Bakery Sales Analytics (Databricks) — Project 29

A hands-on Databricks BI project where I ingested a bakery sales dataset, structured it into tables (CSV/JSON), explored volume + schema behavior, and moved from SQL queries to dashboard-ready visualizations—showing how modern BI can go from raw files → governed tables → insights fast.


![Visualization 1](https://github.com/iyanusol/Bakery-Sales-Databricks-/blob/main/Images/visualization-1.png)
---

## 🔎 Project Overview
This project demonstrates an end-to-end analytics workflow inside **Databricks**, including:
- Loading multiple datasets (CSV + JSON) into Databricks
- Creating and validating **tables** for analysis (structured + semi-structured data)
- Working with **volumes / file paths** and table creation patterns
- Writing **SQL queries** and turning them directly into **visualizations / dashboards**
- Understanding how this can scale with real-world data pipelines (e.g., **Fivetran → Databricks**)

---

## 🧱 Data & Tables (Files → Volumes → Tables)

### Files in the workspace
These screenshots show the dataset staged in Databricks storage and ready for ingestion.

#### Files view (Part 1)
![Databricks Files 1](https://github.com/iyanusol/Bakery-Sales-Databricks-/blob/main/Images/files-1.png)

#### Files view (Part 2)
![Databricks Files 2](https://github.com/iyanusol/Bakery-Sales-Databricks-/blob/main/Images/files-2.png)

---

### Loading Data into Databricks
This shows the ingestion step where data is loaded and prepared for table creation and analysis.

![Load Data](https://github.com/iyanusol/Bakery-Sales-Databricks-/blob/main/Images/Load%20DATA.png)

---

### JSON Table Creation
This demonstrates working with semi-structured data (JSON) and converting it into a queryable table.

![JSON Table](https://github.com/iyanusol/Bakery-Sales-Databricks-/blob/main/Images/JSON%20Table.png)

---

## 🧠 Why Volumes + Tables Matter
In real analytics environments, “just having files” isn’t enough.
You need:
- **Reliable storage locations (volumes / managed locations)**
- **Consistent table structures (schema)**
- **Repeatable ingestion patterns (pipelines / connectors)**

Databricks makes this workflow practical by letting you:
- store and manage data at scale,
- define tables for SQL-based analytics,
- layer governance and access control later as you grow.

---

## 🔌 Scaling the Same Workflow with Fivetran + Multiple Datasets
In production, teams often don’t manually upload CSVs/JSON.  
Instead, data comes from multiple tools (CRM, payments, marketing, operations), and a connector like **Fivetran** can automate ingestion into Databricks.

This project mirrors that idea:
- multiple inputs (CSV + JSON),
- standardized tables,
- queries that can join across datasets,
- dashboards built directly from trusted table structures.

> Example real-world flow: **Google Drive / SaaS Apps → Fivetran → Databricks → SQL → Dashboard**

---

## 🧾 Query → Dashboard (Fast BI Inside Databricks)
A key learning here is how you can go **straight from SQL query results to visualizations**, without switching tools.

### Query-to-dashboard workflow (1)
![Query to Dashboard 1](https://github.com/iyanusol/Bakery-Sales-Databricks-/blob/main/Images/query%20to%20dashboard-1.png)

### Query-to-dashboard workflow (2)
![Query to Dashboard 2](https://github.com/iyanusol/Bakery-Sales-Databricks-/blob/main/Images/query%20to%20dashboard-2.png)

### Query-to-dashboard workflow (3)
![Query to Dashboard 3](https://github.com/iyanusol/Bakery-Sales-Databricks-/blob/main/Images/query%20to%20dashboard-3.png)

---

## 📊 Visualizations
This section shows how the analysis becomes dashboard-ready visuals.

### Visualization view
![Visualization 1](https://github.com/iyanusol/Bakery-Sales-Databricks-/blob/main/Images/visualization-1.png)

### Dashboard sample
![Dashboard Sample](https://github.com/iyanusol/Bakery-Sales-Databricks-/blob/main/Images/dashboard%20sample%201.png)

---

## 🧩 Databricks Environment Walkthrough
These images show key areas of the Databricks environment used during the build.

### Databricks (1)
![Databricks 1](https://github.com/iyanusol/Bakery-Sales-Databricks-/blob/main/Images/databricks-1.png)

### Databricks (2)
![Databricks 2](https://github.com/iyanusol/Bakery-Sales-Databricks-/blob/main/Images/databricks-2.png)

### Databricks (3)
![Databricks 3](https://github.com/iyanusol/Bakery-Sales-Databricks-/blob/main/Images/databricks-3.png)

---

## 🧠 Key Insights (What this project proves)
This project demonstrates the ability to:
- Build an analytics workflow in Databricks from **raw data → tables → insights**
- Work with both **structured and semi-structured (JSON)** datasets
- Use **SQL** to explore patterns and translate findings into business-ready outputs
- Move from **query to visualization** quickly (BI speed + iteration)
- Understand how tooling like **Fivetran** fits into real data engineering pipelines

---

## 🛠️ Tech Stack
- **Databricks** (SQL, tables, dashboards/visuals)
- **CSV + JSON ingestion**
- **Data modeling concepts** (tables, schema, query patterns)
- **Pipeline mindset**: (Fivetran-style ingestion → analytics layer → BI layer)

---
![Databricks 1](https://github.com/iyanusol/Bakery-Sales-Databricks-/blob/main/Images/databricks-1.png)


---

### 👤 Author
**Iyanu Adebara**  
BI / Analytics • Power BI • SQL • Databricks
