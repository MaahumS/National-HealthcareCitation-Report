# 🏥 Nursing Home Health Citations Dashboard  

## 📍 Project Overview
- This report analyzes U.S. nursing home health deficiency citations published by CMS to provide a national-level view of compliance trends and risk patterns.  
- I built an interactive Power BI dashboard that allows users to explore citation volume, deficiency types, severity levels, and compliance outcomes across states and facilities.
  
---

## 💼 Dataset Context
This dataset was sourced from the Centers for Medicare & Medicaid Services (CMS) and contains hundreds of thousands of nursing home citation records across the United States.  


**KPI's:**
- `Total Citations`
- `Total Facilities Surveyed`
- `Deficiency Category`
- `Scope Severity Code`
- `Average Days to Correct`
- `Total Waivers Granted`
- `Total Citations Past Non-Compliance`

---

## 🛠️ Tools Used
- **Power BI** – Data modeling, DAX measures, dashboard design, and interactivity  
- **Power Query** – Data cleaning and transformation  
- **Microsoft Excel** – Initial dataset preprocessing  

---

## 🔍 What I Did
- Cleaned and preprocessed the dataset by:
  - Removed duplicate records 
  - Performed necessary data type conversions (uniform dates, ZIP codes converted to text, etc.) 
  - Created calculated fields such as:
  - `Days to Correction` (difference between correction date and survey date)  
  - `Deficiency Status` (e.g., Past Non-Compliance, Waiver Granted, Other Corrected)  
  - Shortened Deficiency Category labels for better readability in visuals 

---

## 👥 Author
- **Maahum Sattar**
