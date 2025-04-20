# 💉 Syringe Request Analysis Dashboard - Boston City and surroundings.

## 📊 Project Overview

This project presents a data-driven Tableau dashboard analyzing **Syringe Pick-Up Requests** in the City of Boston. The goal is to assist public health officials and decision-makers in monitoring syringe request patterns by **date, time, location, and request type**, ultimately helping improve city-wide response and resource allocation.

The dashboard was built using a **dimensional star schema** design and is powered by public datasets sourced from the City of Boston's 311 request portal.

---

## 🌐 Live Dashboard

🔗 [Boston 311: Syring Request Analysis](https://public.tableau.com/shared/2Z5GJYS79?:display_count=n&:origin=viz_share_link)

---

## 📁 Data Sources

- 📥 **City of Boston 311 Request Data**  
  Source: [Analyze Boston - 311 Service Requests](https://data.boston.gov/dataset/311-service-requests)  
  Format: CSV
  
---

## 🏗️ Data Modeling

A **Star Schema** was used to structure the data efficiently in a relational format, consisting of:

### 🧱 Fact Table:
- `fact_syringe`  
  - Includes all syringe-related request facts (timestamps, case details, etc.)

### 🌟 Dimension Tables:
- `dim_date` – Date-related attributes (day, month, year, weekday, etc.)
- `dim_time` – Time-of-day buckets (hour, AM/PM)
- `dim_location` – Geospatial and regional attributes (districts, lat/lng, zip)
- `dim_request` – Request attributes (type, subject, reason)
- `dim_source` – Channel of intake (phone, app, web, etc.)

---

## 📌 Dashboard Features

- **Daily Overview:**  
  Focused analysis on requests made on a selected anchor day using a relative date filter.

- **Time Series Trends:**  
  Shows volume of syringe requests over time with drill-down capabilities (weekly/monthly/yearly).

- **Geographic Distribution:**  
  Map-based view of request density by neighborhood and zip code.

---

## 📂 Project Files

| File/Folder | Description |
|-------------|-------------|
| `DataModeling_Boston311.ipynb` | Data modeling script using Pyspark |
| `boston311_datacleaning` | Data extraction and cleaning script |
| `README.md` | Project documentation |

---

## 📈 Tools Used

- **Tableau Public** – Data visualization
- **Pyspark/SQL** – Data modeling and transformation
- **Python** – Preprocessing and data cleaning
- **Excel** – Initial data exploration and cleanup

---

## 🧠 Insights & Impact

- Identified hotspots for syringe pickup requests.
- Analyzed performance of departments handling the cases.
- Provided stakeholders with a real-time view for operational planning.

---

## 🔗 Links

- 🔗 Tableau Public Dashboard: [https://public.tableau.com/shared/KFK5KJBSF?:display_count=n&:origin=viz_share_link](url)
- 📊 Data Source: [https://data.boston.gov/dataset/311-service-requests](url)

---

## Data Model - ER Diagram
![image](https://github.com/user-attachments/assets/b3497452-67d9-4b86-9744-83a8d1531fdc)



---

## 📬 Contact

**Gandharva Sudhir Tatkare**  
📧 Email: [tatkare.gandharva@gmail.com](url) 
🔗 LinkedIn: [https://www.linkedin.com/in/gandharva-tatkare/](https://www.linkedin.com/in/gandharva-tatkare/)

---

