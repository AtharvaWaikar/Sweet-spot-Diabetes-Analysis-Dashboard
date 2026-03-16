Portfolio :- 
---
Linkedln:- https://www.linkedin.com/in/atharva-waikar-a95a042b5/
---
Github:- https://github.com/AtharvaWaikar
---

# 🩺 Diabetic Risk Analysis Dashboard (Power BI)

> An interactive healthcare analytics dashboard built using Microsoft Power BI to assess diabetic risk using key medical indicators.

---

## 📌 Project Overview

The **Diabetic Risk Analysis Dashboard** is designed to analyze patient health data and evaluate the risk of diabetes based on critical indicators such as:

- **Age**
- **BMI Category**  
  - Underweight  
  - Normal  
  - Overweight  
  - Obese  
- **Pregnancy Range**

The dashboard enables dynamic filtering and provides real-time analytical insights into diabetic trends and health risk factors.

---

## 🎯 Project Objectives

- Analyze diabetic patient data  
- Identify risk patterns across age groups  
- Understand the impact of BMI, glucose, and blood pressure  
- Provide a visual **Diabetic Risk Meter**  
- Enable interactive health-based filtering  

---

## 📊 Key Dashboard KPIs

| KPI | Description |
|-----|------------|
| 👥 Total Patients | Total number of patients in dataset |
| ⚖️ Average BMI | Mean Body Mass Index |
| 🧪 Average Glucose | Mean glucose level |
| 🤰 Average Pregnancies | Average pregnancy count |
| ❤️ Average Blood Pressure | Mean blood pressure level |

---

## 📈 Visualizations Included

### 📊 Analytical Charts

- Blood Pressure by Age  
- Average Glucose by Age  
- Diabetic Risk by BMI Category  
- Risk Distribution Chart  

### 🎯 Gauge Visualization

- **Diabetic Risk Meter** (Visual risk indicator)

### 🎛 Interactive Slicers

Users can dynamically filter data using:

- Age  
- BMI Category  
- Pregnancy Range  

---

## 🧠 Key Insights & Impact

- Identifies high-risk age groups  
- Highlights correlation between BMI and glucose levels  
- Evaluates impact of pregnancy count on diabetic probability  
- Supports preventive healthcare analysis  
- Helps in data-driven health decision-making  

---

## Dashboard Screenshot

![Dashboard Screenshot](Dashboard%20SC01.jpg)

## 🛠 Tools & Technologies Used

- **Microsoft Power BI**
- **DAX (Data Analysis Expressions)**
- **Power Query**
- **Data Cleaning & Transformation**
- **Interactive Dashboard Design**

---

## 🧮 Sample DAX Measures

```DAX
Total Patients = COUNT(Patients[PatientID])

Average BMI = AVERAGE(Patients[BMI])

Average Glucose = AVERAGE(Patients[Glucose])

Average Pregnancies = AVERAGE(Patients[Pregnancies])
