# Employee Absentees Analysis & Prediction 

An end-to-end data science project written in Python (Jupyter Notebook) designed to analyze, visualize, and model workforce absenteeism patterns. This project leverages an optimization framework to help Human Resource departments uncover key drivers of absenteeism and implement proactive retention strategies.

---

## Table of Contents
* [Project Overview](#-project-overview)
* [Key Features & Workflow](#-key-features--workflow)
* [Tech Stack](#%EF%B8%8F-tech-stack)
* [Dataset Description](#-dataset-description)
* [Future Scope](#-future-scope)

---

## Project Overview
Employee absenteeism can drastically hinder organizational productivity. This project processes historical employee records to:
1. Discover demographic and professional patterns contributing to lost work hours.
2. Build data-driven pipelines to classify or forecast potential absenteeism trends.

---

## Key Features & Workflow

The Python code in the Jupyter Notebook covers the entire data pipeline step-by-step:

### 1. Data Ingestion & Preprocessing
* **Exploratory Data Analysis (EDA):** Checking for missing entries, identifying statistical distributions, and removing duplicate data.
* **Feature Engineering:** Extracting relevant timelines (e.g., months, seasons) and encoding categorical labels.
* **Handling Outliers:** Isolating or smoothing unusual variances in absentee metrics (like extreme hours missed).

### 2. Analytical Visualizations
* **Distribution Histograms:** Examining age, distance to work, and service time trends.
* **Correlation Matrices:** Finding hidden relationships between social habits (e.g., smoking, drinking), family factors (children, pets), and missed hours.
* **Categorical Breakdowns:** Visualizing absenteeism rates across distinct organizational departments or medical reasons.

### 3. Predictive Modeling
* **Data Splitting:** Partitioning datasets into clean training and testing matrices via scikit-learn metrics.
* **The `predictive_praba` Framework:** Implementing the custom core modeling function or class architecture to cleanly manage pipeline inputs, handle numerical variances, and handle the data distribution constraints.
* **Performance Assessment:** Tracking project validity via regression errors or classification metrics to evaluate overall forecasting stability.

---

## Tech Stack

* **Language:** Python 3.x
* **Environment:** Jupyter Notebook
* **Libraries Used:**
  * `pandas` & `numpy` - Robust data manipulation and matrix tracking
  * `matplotlib` & `seaborn` - Advanced scientific charting and graphical plotting
  * `scikit-learn` - Machine learning pipelines, scaling, and validation tools

---

## Dataset Description

The analysis primarily evaluates the following features:
* **Demographics:** Age, Education level, Children, Pets, Body Mass Index (BMI).
* **Workplace Metrics:** Distance from residence to work, Service time, Daily workload average, Transportation expense.
* **Absentee Factors:** Reason for absence (ICD classifications), Month of absence, Day of the week, Absenteeism time in hours (Target metric).

---

## Future Scope
* **Deep Learning Integration:** Testing multi-layer neural networks for complex absenteeism classification tasks.
