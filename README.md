# Global Electric Vehicles Analysis 🚗⚡

## 1. Project Overview

This project focuses on analyzing **global electric vehicle (EV) adoption trends** using Big Data Analytics techniques. The dataset (sourced from Kaggle – *Electric Vehicle Population Data*) contains ~130,000 records of EV registrations across multiple years up to 2023.

The objective is to study the **growth of EV adoption**, understand key factors such as range, incentives, and manufacturer trends, and apply predictive analytics to forecast future EV sales. The project is implemented in **Jupyter Notebook with PySpark** for scalable big data operations.

**Repository Details:**

* **Name:** Global-EV-Analysis
* **Language:** Python (PySpark, Pandas, Matplotlib)
* **Description:** Big Data Analytics project on electric vehicle trends, adoption, and forecasting.
* **Dataset Source:** Kaggle – Electric Vehicle Population Data
* **Activity:** Academic project for Big Data Analytics coursework.

---

## 2. Analysis Workflow

The workflow of this project is structured step-by-step:

### 🔹 Data Loading & Cleaning

* Imported dataset (~130K EV records) using PySpark.
* Checked schema, standardized data types, removed null and invalid records.

### 🔹 Data Preprocessing

* Handled missing values in *MSRP* and *CAFV Eligibility*.
* Removed duplicates using VIN (unique vehicle ID).
* Outlier detection for *Electric Range* and *MSRP*.

### 🔹 Exploratory Data Analysis (EDA)

* Distribution plots for **EV range**.
* Count plots for **EVs by manufacturer**.
* Line chart of **EV adoption by year**.
* Geographic heatmap of **EV registrations by state/county**.

### 🔹 Feature Engineering

* Grouped EVs by manufacturer and type (BEV vs PHEV).
* Categorized electric range into *Low (<100 miles), Medium (100–250 miles), High (>250 miles)*.
* Extracted adoption trends by year and incentive eligibility.

### 🔹 Analytical Operations

* Compared **BEV vs PHEV growth over time**.
* Studied **impact of CAFV (Clean Fuel Incentives)** on adoption.
* Analyzed **pricing vs range** correlation.

### 🔹 Mini Project (Predictive Analysis)

* Implemented predictive models (Linear Regression, Random Forest Regressor) using PySpark MLlib.
* Forecasted EV adoption trends for the next 5 years.

---

## 3. Key Insights

1. **Rapid Growth Post-2015** – EV registrations increased significantly after 2015, especially for BEVs.
2. **Manufacturer Dominance** – Tesla leads long-range BEVs, while Nissan Leaf and Chevy Bolt dominate mid-range EVs.
3. **Policy & Incentives Matter** – EVs eligible for CAFV incentives show much higher adoption.
4. **Geographic Concentration** – California, Washington, and New York have the highest EV penetration.
5. **Range Evolution** – Modern EVs (2020–2023) often exceed 300 miles, reducing range anxiety.

---

## 4. Future Scope

* Integrate **real-time EV sales and charging infrastructure datasets**.
* Expand analysis to a **global scale beyond U.S. states**.
* Apply **time-series forecasting models (ARIMA, Prophet)** for long-term EV adoption prediction.
* Explore the **link between EV adoption and CO₂ emission reductions**.

---

## 5. Tools & Technologies

* **Big Data Framework:** PySpark (RDD, DataFrames, MLlib)
* **Visualization:** Matplotlib, Seaborn
* **Language:** Python (Jupyter Notebook)
* **Dataset Source:** Kaggle EV Population Data

---

