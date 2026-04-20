# ☔ India Rainfall Analysis (1901–2015)

## 🚀 Project Overview

This project analyzes **115 years of rainfall data in India (1901–2015)** to uncover long-term climate patterns, seasonal contributions, and regional variability.

An interactive Excel dashboard was built to transform raw rainfall data into meaningful insights for better understanding of climate behavior.

---

## 🎯 Objectives

* Analyze **long-term rainfall trends in India**
* Compare rainfall across **different time periods (1901–1950 vs 1951–2015)**
* Study **seasonal contribution to total rainfall**
* Identify **state-wise rainfall variability and patterns**

---

## 📊 Dashboard Features

### 🔹 Key Insights Visualized

* All-India Annual Rainfall Trend (115 years)
* Seasonal Contribution (Monsoon vs Other Seasons)
* Period Comparison (Before vs After 1950)
* State-wise Rainfall Variability (Standard Deviation)
* State-wise Average Rainfall Distribution

---

## 📈 Key Findings

* 🌧 **Monsoon Dominance:** ~75% of total rainfall occurs during Jun–Sep
* 📊 **Stable Long-Term Average:** India’s rainfall remains around ~1411 mm despite fluctuations
* 📉 **Extreme Years:** Clear wettest and driest years identified
* 🌍 **Regional Variation:** Coastal regions receive highest rainfall, while Rajasthan & Haryana receive lowest
* ⚠️ **Climate Signal:** Slight seasonal shifts observed over time

---

## 🧹 Data Preparation

* Cleaned and standardized dataset
* Handled missing values
* Created a **Period column** for time comparison
* Structured data for Pivot Tables and analysis

---

## 🛠️ Methodology

### ✔ Step 1: Data Understanding

Explored dataset structure (year, seasonal, state-wise rainfall)

### ✔ Step 2: Data Cleaning

Formatted columns and ensured consistency

### ✔ Step 3: Feature Engineering

Created **Period column**:

```excel
=IF(Year<=1950,"1901-1950","1951-2015")
```

### ✔ Step 4: Analysis using Pivot Tables

* Annual trend (Line chart + Moving Average)
* Variability (Standard Deviation)
* Period comparison (Bar chart)
* Seasonal contribution (Stacked Area chart)

### ✔ Step 5: Dashboard Design

* KPI cards
* Interactive slicers (Year, State, Period)
* Clean layout for storytelling

---

## 🎛️ Interactivity

* Slicers for:

  * State
  * Year
  * Period

👉 Enables dynamic and user-driven analysis

---

## 🛠️ Tools Used

* Microsoft Excel
* Pivot Tables
* Data Visualization Techniques

---

## 📂 Project Structure

```id="rain12"
├── data/
├── dashboard/
└── README.md
```

---

## 📸 Dashboard Preview

<img width="1316" height="429" alt="image" src="https://github.com/user-attachments/assets/51a550be-65fd-41de-8ef2-9855e5e5fa6b" />


---

## 🏁 Conclusion

This project highlights how rainfall patterns in India have evolved over more than a century. It emphasizes the critical role of monsoon and the importance of data-driven insights for agriculture, water management, and climate planning.

---

## 🙌 Acknowledgment

Dataset sourced from Kaggle and public rainfall datasets.

---



