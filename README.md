# 💰 Loan Default Data Analysis 

## 📌 Project Overview
This project focuses on analyzing **loan default data** using **Microsoft Power BI** to identify default patterns, risk factors, and trends.  
The analysis is performed on data sourced from a **CSV file**, using advanced data preparation, DAX calculations, and interactive visuals.

---

## 📁 Data Source
- **Format**: CSV file (`.csv`)
- **Dataset**: Loan Default Data
- Imported directly into Power BI

---

## 🔍 Data Profiling & Preparation
- Data profiling to understand structure and quality
- Data understanding and exploratory analysis
- Data transformation and data cleaning using **Power Query Editor**
- Handling missing, invalid, and inconsistent values

---

## ✔️ Data Validation
- Verified data accuracy after transformation
- Checked consistency between source data and report outputs
- Ensured calculated measures align with business logic

---

## 📊 Visualizations
- **Line Chart** – trend analysis over time
- **Ribbon Chart** – ranking and comparison across categories
- **Decomposition Tree** – drill-down analysis of loan defaults
- Decomposition tree created using **SWITCH DAX logic**

---

## 📐 DAX Functions Used (Brief Explanation)
- `SUM()`, `SUMX()` – aggregations and row-based calculations  
- `FILTER()` – filtered context calculations  
- `NOT()`, `ISBLANK()` – logical and null handling  
- `CALCULATE()` – modified filter context  
- `AVERAGE()`, `AVERAGEX()` – mean calculations  
- `MEDIANX()` – median over expressions  
- `COUNTROWS()` – record counting  
- `DIVIDE()` – safe division  
- `VALUES()` – distinct value retrieval  
- `ALL()`, `ALLEXCEPT()` – filter control  
- **YOY & YTD** – time-based performance calculations  

---

## 📈 Key Insights
- Identification of high-risk loan segments
- Trend analysis of loan defaults over time
- Clear understanding of key contributors to default using decomposition tree
- Improved visibility into category-wise and time-based risk patterns

---

## 📸 Screenshots
#### 1. Snapshot of DAX expression used to calculate measures in this project:
![image1](https://github.com/prasannak2405/PowerBI_Dashboard_7/blob/8872036aeb6687be2bcd1f7f749670539c902ae8/image/LD_M%26CC1.png)

#### 2. Snapshot of DAX expression used to calculate measures in this project:
![image2](https://github.com/prasannak2405/PowerBI_Dashboard_7/blob/8872036aeb6687be2bcd1f7f749670539c902ae8/image/LD_M%26CC2.png)

#### 1. Snapshot of DAX expression used to calculate calculated column in this project:
![image3](https://github.com/prasannak2405/PowerBI_Dashboard_7/blob/8872036aeb6687be2bcd1f7f749670539c902ae8/image/LD_M%26CC3.png)



---

## 📁 Repository Contents
- Power BI report file (`.pbix`)
- Screenshots
- PDF report
- README.md

---

## ✅ Conclusion

This project demonstrates end-to-end **loan risk analysis using Power BI**, covering data profiling, validation, advanced DAX calculations, and interactive visual storytelling
