# Uberlytics
An end-to-end analysis and interactive dashboard on Uber trip data using Python and Power BI.


# 🚗 Uber Trip Data Analysis & Power BI Dashboard

This project presents a complete data analysis workflow on Uber ride data using **Python (Jupyter Notebook)** and a fully interactive **Power BI dashboard**.

It combines exploratory data analysis (EDA), machine learning classification, and dashboard creation to uncover insights into trip patterns, usage behavior, and trip purposes.

---

## 📁 Project Components

| File                          | Description                                                             |
|-------------------------------|-------------------------------------------------------------------------|
| `Uber_DA.ipynb`               | Jupyter Notebook with data cleaning, EDA, visualizations, and ML models |
| `Uber_PowerBi_Dashboard.pbix` | Interactive dashboard created in Power BI                               |
| `uber_cleaned_for_powerbi.csv`| Cleaned dataset used in Power BI                                        |

---

## 📊 Key Objectives

- 🔍 Analyze trip data to identify trends by **hour, day, month**
- 🧹 Clean and preprocess raw Uber trip data
- 📈 Visualize purpose, type, and duration of trips
- 🤖 Build a **trip type classifier (Business vs Personal)**
- 📊 Create an **interactive Power BI dashboard** for stakeholders

---

## 🧪 Exploratory Data Analysis (Python)

Performed in `Uber_DA.ipynb`, the notebook includes:

- Time-based trends (hourly, daily, monthly)
- Trip purpose frequency
- Category-wise (Business/Personal) breakdown
- Duration and distance statistics
- Correlation heatmap
- Linear Regression & Classification using Scikit-learn

---

## 📈 Power BI Dashboard Features

The dashboard includes the following visuals:

- 📅 **Trips by Day of Week** (with Business vs Personal split)
- ⏰ **Trip by Hour of Day**  (with Business vs Personal split)
- 🧭 **Trip Purpose Distribution**
- 📆 **Monthly Trip Tred**
- 📌 **Trips by Category (pie chart )**
- 🧮 **KPI Cards** (Total Trips, Total Miles)
- 🎛 **Slicers** for Category and Month

> 🔗 *File: `Uber_PowerBi_Dashboard.pbix`*

---

## 🛠 Tools & Technologies

| Tool                                               | Purpose                  |
|----------------------------------------------------|--------------------------|
| Python (Pandas, Matplotlib, Seaborn, Scikit-learn) | Data processing, EDA, ML |
| Power BI                                           | Interactive dashboard    |
| Jupyter Notebook                                   | Analysis notebook        |

---

## 🧠 Machine Learning

Built in the notebook:
- ✅ **Trip Type Classifier**: Predict if a trip is Business or Personal
- ✅ Simple Linear Regression for duration/miles relation
- 📌 Used `train_test_split`, `accuracy_score`, `classification_report`

---
