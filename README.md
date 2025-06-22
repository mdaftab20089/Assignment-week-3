# Assignment-week-3

# 🚗 Used Car Price Analysis – EDA

## 📘 Project Overview

This is **Week 3's Assignment** for the Data Analytics course.  
The task is to **take any dataset** and perform **data visualization and exploratory data analysis (EDA)**.

In this notebook, we have chosen a **Used Car Price Dataset**, with the aim of understanding the factors that influence the price of a used car.

---

## 🧾 Problem Statement

> Analyze the used car’s price using EDA and visualizations to identify which factors have the most impact on the car price.

---

## 📊 Dataset Description

The dataset contains a total of **14 features**, out of which:
- 3 are of integer type (e.g., `Year`, `Kilometers Driven`, `Price`)
- Others include categorical features (e.g., `Fuel Type`, `Transmission`, `Owner Type`)

---

## 🔍 Key Analysis Performed

- **Univariate and Bivariate Analysis**
- **Distribution Plots** and **Boxplots** for outlier detection
- **Correlation Heatmap** to identify linear relationships
- **Insights on:**
  - Engine and Power correlation
  - Relationship of Price with Mileage, Car Age, Year, etc.
  - Car Age vs Kilometers Driven trend

---

## 📈 Highlights from Heatmap

- **Engine** is highly correlated with **Power** (0.86)
- **Price** is positively correlated with both **Engine** (0.69) and **Power** (0.77)
- **Mileage** has a negative correlation with Engine, Power, and Price
- **Car Age** negatively impacts Price and Mileage but increases with Kilometers Driven

---

## 🛠 Tools & Technologies Used

- Python (Pandas, NumPy)
- Matplotlib, Seaborn
- Jupyter Notebook
--------------------------------

