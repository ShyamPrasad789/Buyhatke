# 📊 Business Analyst Assignment — Buyhatke Audio Data Analysis

## 🧠 Overview
This project demonstrates an end-to-end business analysis workflow on **Buyhatke’s Audio Product Sales Data**. It includes data cleaning, visualization, and presentation deliverables (Excel dashboard + PowerPoint strategy deck). The objective is to derive actionable insights and present them with professional-quality visuals.

---

## 📁 Project Structure
    ├── sample-data-audio.csv                                  # Source datase
    ├── Business_Analyst_Assignment_Analysis_Enhanced.xlsx     # Cleaned Excel dashboard
    ├── Buyhatke_Cab_Compare_Strategy_Enhanced_Final.pptx      # Strategy presentation
    ├── analysis_images/                                       # Auto-generated charts
    └── README.md                                              # Documentation

---

## ⚙️ Features
✅ Automated data cleaning and preprocessing  ll
✅ Interactive Excel dashboard with KPIs  
✅ Conditional formatting (Top/Bottom performers)  
✅ Chart generation (Top 10 Products, Revenue Trend, Price Distribution)  
✅ Auto-removal of empty sheets/tables  
✅ Light-blue corporate theme with ₹ currency formatting  

---

## 🧹 Data Cleaning Workflow
Performed automatically by `analysis.py`:
- Removed duplicates and null rows  
- Cleaned product names and standardized text  
- Parsed and formatted dates  
- Converted prices to numeric (₹ INR)  
- Removed invalid/outlier values  
- Imputed missing data using median values  
- Added calculated columns: `quantity`, `revenue`, and `month`  

---

## 📊 Excel Dashboard Details
### 🟦 Dashboard Sheet
- **KPIs:**
  - Total Revenue  
  - Top Product  
  - Revenue Growth (MoM %)  
  - Average Price  
- **Charts:**
  - Top 10 Products by Revenue  
  - Monthly Revenue Trend  
  - Price Distribution Histogram  

### 📘 Product Summary
- Structured Excel table with ₹ formatting and filters  
- Conditional formatting:
  - 🟩 Top 3 products highlighted green  
  - 🔴 Bottom 3 products highlighted red  

### 📅 Revenue by Month
- Month-wise revenue table and line chart  
- Highlights growth percentage in latest month  

### 💡 Top 10 Insights
- Key takeaways derived from the data  
- Includes synergy-driven business recommendations  

### 📄 Raw Data
- Cleaned dataset after preprocessing (for transparency)

---

## 🧰 Tools & Technologies
- **Python 3.10+**
- Libraries: `pandas`, `numpy`, `matplotlib`, `xlsxwriter`, `openpyxl`
- **Microsoft Excel** for dashboard visualization  
- **PowerPoint** for presentation slides  

---

## 🚀 How to Run

### 1️⃣ Install dependencies
```bash
pip install pandas numpy matplotlib xlsxwriter openpyxl
