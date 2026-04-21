# 🏠 Airbnb Data Analysis — Power BI Dashboard

An end-to-end data analytics project analyzing Airbnb listings data to uncover insights about pricing, host performance, availability trends, and licensing compliance.

---

## 📌 Project Overview

This project explores Airbnb listings data through a complete analytics pipeline — from raw data cleaning to interactive visual reporting. The goal is to help stakeholders understand market dynamics, host behavior, and property availability patterns.

---

## 🗂️ Dashboard Pages

| Page | Description |
|------|-------------|
| **Overview** | High-level KPIs, listing distribution, revenue trends, and category breakdowns |
| **Host Analysis** | Deep dive into host performance, listing counts, and comparative metrics |
| **License & Compliance** | Analysis of licensed vs. unlicensed properties and regulatory compliance |
| **Availability** | Scatter and bar charts showing availability patterns and booking behavior |

---

## 🛠️ Tools & Technologies

| Tool | Purpose |
|------|---------|
| **Microsoft Excel — Power Query** | Data ingestion, cleaning & transformation |
| **Power BI — Data Model** | Relational modeling, DAX measures & calculated columns |
| **Power BI — Report View** | Interactive dashboards & visualizations |

---

## 🔄 Project Workflow

```
Raw Data (CSV)
     │
     ▼
Excel Power Query
  ├── Remove duplicates & nulls
  ├── Standardize column formats
  ├── Filter irrelevant records
  └── Shape & transform tables
     │
     ▼
Power BI Data Model
  ├── Define table relationships
  ├── Create DAX measures (KPIs, aggregations)
  └── Build calculated columns
     │
     ▼
Power BI Report
  ├── Overview Dashboard
  ├── Host Analysis
  ├── License & Compliance
  └── Availability Analysis
```

---

## 📊 Visualizations Used

- **Cards** — KPI metrics (total listings, average price, etc.)
- **Clustered Column Charts** — Category comparisons over dimensions
- **Clustered Bar Charts** — Host and compliance breakdowns
- **Donut Charts** — Proportional distribution of listing types
- **Scatter Chart** — Availability vs. pricing correlation
- **Slicers** — Interactive filters for dynamic exploration

---

## 📁 Repository Structure

```
📦 airbnb-powerbi-analysis
 ┣ 📊 Airbnb_Dashboard.pbix       # Power BI report file
 ┣ 📂 data/
 ┃ ┗ 📄 airbnb_raw_data.csv       # Raw source data
 ┣ 📂 screenshots/                # Dashboard preview images
 ┗ 📄 README.md
```

---

## 🚀 How to Use

1. Clone or download this repository
2. Open `Airbnb_Dashboard.pbix` in **Power BI Desktop**
3. If needed, update the data source path to point to the local `data/` folder
4. Explore the 4 interactive report pages using slicers and filters

---

## 💡 Key Insights

- Identified top-performing hosts by listing count and availability rate
- Highlighted compliance gaps between licensed and unlicensed properties
- Revealed seasonal availability patterns affecting booking rates
- Compared pricing distribution across different listing categories

---

## 👤 Author

**Saeed**
📧 Connect on Linkedin -> [www.linkedin.com/in/elsaeed-khairy-813a6b239

](#) | 💼 [GitHub](#)

---
## 📊 Dashboard Preview
<p align="center">
  <img src="https://github.com/user-attachments/assets/552b7c54-a9d7-4bbb-9323-046972b2a3dd" width="45%" />
  &nbsp;&nbsp;&nbsp;&nbsp;
  <img src="https://github.com/user-attachments/assets/c86e7d00-034c-4b32-a583-f8f696dfee45" width="45%" />
</p>

<br>

<p align="center">
  <img src="https://github.com/user-attachments/assets/e5f5db8f-b199-4b74-b259-d4044647c892" width="45%" />
  &nbsp;&nbsp;&nbsp;&nbsp;
  <img src="https://github.com/user-attachments/assets/901e72c8-4c61-43d8-9b5c-e48c713620d3" width="45%" />
</p>
> *Built with Excel Power Query + Power BI | Data Cleaning · Modeling · Visualization*
