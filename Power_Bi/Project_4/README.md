# 📊 Tracker Treningowy – KajoDataSpace  
**Power BI • Python • Data Modeling • Analytics**

## 🎯 Project Goal
This project analyzes the relationship between **training volume, cardio activity, and body measurements over time** using real data from a personal training log.

The goal was to build a **complete analytical solution** — from data modeling and ETL in Python to an **interactive Power BI dashboard** — enabling long-term progress tracking and trend analysis.

The project is based on real data collected within the **KajoDataSpace training system**.

---

## 📌 Analytical Problem
The analysis focuses on answering key questions:

- How does **strength training volume** impact body weight and waist circumference?
- How does **cardio activity** change over time and across months?
- Is training **regularity** improving?
- Can all training and body metrics be analyzed consistently on a shared time axis?

---

## 🧠 Key Insights
🔹 Strength training volume shows a clear upward trend over time  
🔹 Record monthly volume reached **32,000 kg (+129% m/m)**  
🔹 Waist circumference decreased by **9 cm**, despite fluctuations in body weight  
🔹 Training regularity improved significantly in later months  
🔹 Strength training dominates total workload (**~85% vs. cardio ~15%**)

📊 **Conclusion:**  
Consistent increases in training volume and regularity are strongly associated with positive body composition changes, especially waist circumference reduction.

---

## 🧱 Data Model
A **custom star schema model** was designed and implemented in Python:

**Fact tables**
- `fact_activity` – training activities (strength & cardio)
- `fact_body_metrics` – body measurements

**Dimension tables**
- `dim_date`
- `dim_activity`
- `dim_exercise`

The model was designed for **easy scalability** and future metric expansion.

---

## ⚙️ Scope of Work
- Data cleaning and standardization (Python)
- ETL processes for dates, time, and activity types
- Aggregation of:
  - monthly strength training volume (kg)
  - cardio activity (minutes)
- Merging training data with body measurements
- KPI and measure creation using DAX
- Interactive dashboard design in Power BI

---

## 🛠️ Technologies Used
- **Python** – ETL & data preparation  
- **Power BI** – data modeling, DAX, visualization  
- **Power Query** – transformations  
- **DAX** – KPIs and business metrics  
- **Markdown** – documentation  

---

## 🖼️ Dashboard Preview

<img width="1412" height="794" alt="Tracker treningowy - KajoDataSpace" src="https://github.com/user-attachments/assets/2dfebd1a-97dd-42e4-98ad-8fc79dd6afa5" />
