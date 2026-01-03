# 🏥 Hospital Performance & Patient Analytics Dashboard

## 📊 Project Overview
This Power BI project provides a 360-degree view of hospital operations and patient demographics from **2018 to 2021**. By analyzing over **25 Million patient records**, this dashboard enables healthcare administrators to identify trends in specialized care, manage case-type distributions, and monitor seasonal patient surges.

---

## 🚀 Key Features & Visuals
* **Executive Summary KPIs:** Real-time tracking of Total Patients (25M), Average Patients per period (54), and Quarterly comparisons.
* **Patient Case Analysis:** Donut chart visualization showing the breakdown between **Outpatients (88.21%)**, **Day Cases (8.36%)**, and **Inpatients (3.43%)**.
* **Demographic Profiling:** Segmentation of patient data by **Adults (85.55%)** vs. **Children (14.45%)**, further filtered by age brackets (0-15, 16-64, 65+).
* **Root Cause Exploration:** Utilized a **Decomposition Tree** to drill down from total patient volume into Year, Month, Specialty, and Specialty Group (e.g., Cardiology -> Heart).
* **Specialty Ranking:** Horizontal bar charts identifying top specialties, led by **Orthopaedics (3.04M)** and **ENT (2.8M)**.

---

## 📈 Key Insights
* **Operational Workload:** Outpatient services represent the vast majority of hospital activity, accounting for over **21.74M** visits.
* **Growth Trends:** Total patient volume grew steadily year-over-year, increasing from **7.03M in 2018** to **7.98M in 2020**.
* **Specialty Focus:** Orthopaedics, ENT, and Ophthalmology are the highest-traffic departments, suggesting a need for resource prioritization in these areas.
* **Late-Year Surge:** Line charts indicate a significant upward trend in outpatient volume moving into 2021, peaking at approximately **629K**.

---

## 🛠️ Technical Stack
* **Power BI Desktop:** Report authoring and dashboard design.
* **DAX (Data Analysis Expressions):** Used for calculating complex measures like "Past Quarter Patient Total" and "Average Patient."
* **Power Query:** Data transformation and cleaning of temporal healthcare records.
* **Decomposition Tree & Line Analysis:** Advanced AI visuals for trend and root-cause analysis.

---

## 💡 How to Use
1.  **Download** the `Project.pbix` file .
2.  Open in **Power BI Desktop**.
3.  Use the **Date Range Slider** to filter data between Jan 2018 and Mar 2021.
4.  Toggle between **Average Patient** and **Total Patient** buttons at the top right to switch metric views across the entire dashboard.
