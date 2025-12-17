# 🎮 Video Game Sales Analysis (1980–2016)

## 📌 Project Overview
This project analyzes global video game sales data from 1980 to 2016 to identify trends across publishers, genres, platforms, regions, and time.  
The objective is to practice end-to-end data analytics including data cleaning, exploratory data analysis (EDA), and visualization using Python.

---

## ❓ Problem Statement
The video game industry spans multiple decades and regions.  
This project aims to understand:
- Which publishers, genres, and platforms dominate global sales
- How sales differ across regions (North America, Europe, Japan, Other)
- How the industry evolved in its early years

---

## 📂 Dataset
- **Source:** Kaggle – Video Game Sales Dataset  
- **Time Period:** 1980–2016  
- **Records:** ~16,500 rows  

### Key Columns
- `Name` – Game title  
- `Platform` – Gaming platform  
- `Year` – Release year  
- `Genre` – Game genre  
- `Publisher` – Publishing company  
- `NA_Sales`, `EU_Sales`, `JP_Sales`, `Other_Sales` – Regional sales (millions)  
- `Global_Sales` – Worldwide sales (millions)

---

## 🧹 Data Cleaning & Preparation
- Removed rows with missing `Year` values
- Converted `Year` to integer format
- Removed rows with missing `Publisher`
- Checked for duplicate records
- Validated data types and summary statistics

---

## 🛠 Tools & Libraries Used
- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Jupyter Notebook  

---

## 📊 Analysis Performed

### 1. Top Contributors Analysis
- Top 5 publishers by global sales
- Top 5 genres by global sales
- Top 5 platforms by global sales

### 2. Publisher-Specific Analysis
- Top 10 Nintendo games by global sales

### 3. Regional Sales Distribution
- Sales share across North America, Europe, Japan, and Other regions

### 4. Regional Comparison
- Comparison of North America vs Europe sales using scatter plots

### 5. Time-Series Analysis
- Regional sales trends from 1980 to 1995

---

## 🔍 Key Insights
- Nintendo is the leading publisher by global sales
- Action, Sports, and Platform genres generate the highest sales
- North America contributes the largest share of global sales
- Japan shows distinct sales patterns compared to Western regions
- Early industry growth was gradual with clear regional differences

---

## ✅ Conclusion
This project demonstrates a complete data analytics workflow from raw data cleaning to insight generation through visualization.  
It highlights practical skills in Python, data manipulation, and exploratory analysis.

---

## 🚀 Future Improvements
- Extend time-series analysis to later years
- Perform genre-wise regional comparison
- Add interactive dashboards using Power BI or Plotly

---

## ▶️ How to Run
1. Clone the repository  
2. Install required libraries  
   ```bash
   pip install pandas numpy matplotlib seaborn
