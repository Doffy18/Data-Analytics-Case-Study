# 💚 Bellabeat Case Study – Data-Driven Wellness Strategy

## 📊 Overview

This project analyzes smart device usage data to uncover behavioral trends in physical activity, sleep, and sedentary time. Insights are used to generate marketing recommendations for **Bellabeat** — a wellness tech company focused on women's health.

The analysis is based on public Fitbit data and aligns with Bellabeat’s mission to empower users through data-informed wellness habits.

---

## 🧠 Business Objective

> **How can Bellabeat use smart device usage patterns to improve engagement, retention, and product positioning across its wellness ecosystem?**

---

## 🔍 Data Source

- 📦 **FitBit Fitness Tracker Data**  
  Public dataset on Kaggle (CC0 license)  
  [View on Kaggle](https://www.kaggle.com/datasets/arashnic/fitbit)

**Selected Tables:**
- `dailyActivity_merged.csv`
- `hourlyCalories_merged.csv`
- `hourlyIntensities_merged.csv`
- `hourlySteps_merged.csv`
- `minutesMETsNarrow_merged.csv`
- `sleepDay_merged.csv`

---

## ⚙️ Tools Used

- **Excel**: Date/time formatting, preliminary cleanup  
- **Python (Pandas, Matplotlib, Seaborn)**: EDA, correlation, visualizations  
- **Jupyter Notebook**: Exploratory analysis and documentation  
- **GitHub**: Version control and portfolio hosting

---

## 🧹 Data Cleaning Summary

- Removed duplicates and nulls  
- Separated date and time columns  
- Standardized datetime formats  
- Rounded numeric columns  
- Dropped unused columns  
- Merged datasets for hourly/daily insights

Details are documented in the `bell_cleaning.ipynb` notebook.

---

## 📈 Key Insights

- Most users do not meet step, sleep, or intensity goals  
- Sleep ≥7 hours → ~43 min less sedentary the next day  
- High activity hours = 4–7 PM  
- Weekend activity dips for many users  
- Strong correlation: steps ↔ calorie burn (ρ ≈ 0.81)

---

## 📢 Recommendations

- Introduce **+1,000 step micro-goals**  
- Launch **“Weekend Warrior” step challenges**  
- Promote **short high-intensity workouts**  
- Trigger **notifications during peak activity windows**  
- Add **sleep coaching** to improve activity indirectly

More details in the [full report](#).

---

## 📌 Project Outcome

If implemented, these strategies can lead to:

- 📈 Higher engagement & retention  
- 🧘‍♀️ Improved wellness outcomes for users  
- 🎯 Stronger brand positioning  
- 💼 Greater ROI on marketing initiatives

---

## 📄 Files in This Repository

| File Name                 | Description                              |
|--------------------------|------------------------------------------|
| `bell_cleaning.ipynb`    | Notebook for data import & cleaning      |
| `bell_analysis.ipynb`    | Notebook for EDA & insights               |
| `bell_report.docx/pdf`   | Final written report (linked externally) |
| `/charts/`               | Exported visuals                         |
| `/data/`                 | Selected CSVs used for analysis          |
| `README.md`              | Project overview (this file)             |

---

## 🔗 View the Final Report
    view report from the files

---

## 👤 Author

**KashiNath**  
Aspired Data Scientist | Data Analytics | Machine Learning  


