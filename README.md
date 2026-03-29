# 🏃 Personal Health & Fitness Dashboard — 2022

> A year-long self-tracking study analysing 237 days of personal health data including daily activity, nutrition, sleep, body composition, and hydration — visualised with **Tableau** and analysed with **Python**.

---

## 📌 Project Overview

This project tracks daily health metrics throughout **2022** (Jan – Dec), covering step counts, caloric burn, sleep duration, body weight, BMI, protein intake, vitamins, minerals, and hydration levels. The goal is to uncover patterns and actionable insights from real personal health data.

**Author:** Om Patel | **Records:** 237 days

---

## 📊 Key Metrics

| Metric | Value |
|---|---|
| Avg Daily Steps | 6,338 |
| Peak Steps (single day) | 36,019 |
| Days with 10,000+ Steps | 67 (28.3%) |
| Avg Calories Burned | 1,960 kcal |
| Avg Nightly Sleep | 6.3 hrs |
| Avg BMI | 24.88 |
| Avg Body Weight | 49.5 kg |
| Avg Daily Protein | 98 g |
| Avg Hydration Level | 67.9% |

---

## 📁 Repository Structure
```
personal-health-dashboard-2022/
│
├── 📂 data/
│   └── health_data.xlsx          # Raw dataset (237 daily records)
│
├── 📂 tableau/
│   └── Health_Dashboard.twbx     # Tableau packaged workbook
│
├── 📂 notebooks/
│   └── health_analysis.ipynb     # Python EDA notebook
│
├── 📂 scripts/
│   └── eda_summary.py            # Standalone Python analysis script
│
├── 📂 images/
│   └── health_dashboard_analysis.png
│
├── requirements.txt
└── README.md
```

---

## 🔍 Key Insights

- Only **28.3%** of days reached the 10,000-step goal
- Average sleep of **6.3 hrs** is below the recommended 8 hrs
- **Vitamin C** intake was consistently near 0% — a notable nutritional gap
- Hydration averaged **67.9%**, below the 80% daily target
- BMI of **24.88** remained in the healthy range throughout the year

---

## 📋 Dataset Columns

| Column | Description |
|---|---|
| `ActivityDay` | Date of record |
| `StepTotal` | Total steps walked |
| `Calories` | Daily calories burned |
| `TotalMinutesAsleep` | Sleep in minutes |
| `WeightKg` | Body weight (kg) |
| `BMI` | Body Mass Index |
| `Protein` | Daily protein (g) |
| `Vitamin A / C` | % of daily recommended value |
| `Calcium / Iron` | % of daily recommended value |
| `Calories from Fat` | Fat-derived calories |
| `Water Level Consumption % Level` | Daily hydration % |

---

## 🛠️ Tools & Technologies

![Tableau](https://img.shields.io/badge/Tableau-E97627?style=flat&logo=tableau&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Excel](https://img.shields.io/badge/Microsoft_Excel-217346?style=flat&logo=microsoft-excel&logoColor=white)
![Pandas](https://img.shields.io/badge/pandas-150458?style=flat&logo=pandas&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat&logo=jupyter&logoColor=white)

---

## 🚀 Getting Started
```bash
# Clone the repo
git clone https://github.com/YOUR_USERNAME/personal-health-dashboard-2022.git
cd personal-health-dashboard-2022

# Install dependencies
pip install -r requirements.txt

# Run analysis
python scripts/eda_summary.py

# Or open notebook
jupyter notebook notebooks/health_analysis.ipynb
```

Open `tableau/Health_Dashboard.twbx` in **Tableau Desktop** or **Tableau Public** for the interactive dashboard.

---

## 📄 License

Personal and academic use only. Data is privately collected.
```

---

**GitHub Topics (paste into the Topics field):**
```
tableau python data-analysis health-analytics pandas matplotlib excel eda personal-project
