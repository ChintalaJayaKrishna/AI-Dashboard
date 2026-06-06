# 🚢 AI Dashboard – Titanic Passenger Survival Analysis

## 📌 Project Overview

The **AI Dashboard – Titanic Passenger Survival Analysis** is an interactive data analytics project developed using **Python** and **Google Colab**. This dashboard transforms raw passenger data into meaningful insights through data cleaning, KPI generation, interactive filtering, and visual storytelling.

By analyzing passenger demographics, ticket information, and survival outcomes, the project uncovers patterns that influenced survival during one of history's most famous maritime disasters.

---

## 🎯 Project Objectives

* Perform data cleaning and preprocessing.
* Explore passenger demographics and characteristics.
* Calculate important Key Performance Indicators (KPIs).
* Identify survival trends and patterns.
* Build interactive visualizations for better decision-making.
* Demonstrate practical applications of data analytics and dashboard development.

---

## 📂 Dataset Information

**Dataset Name:** Titanic_AI_Dashboard.csv

### Dataset Features

| Feature     | Description                       |
| ----------- | --------------------------------- |
| PassengerId | Unique Passenger Identifier       |
| Survived    | Survival Status (0 = No, 1 = Yes) |
| Pclass      | Passenger Class (1st, 2nd, 3rd)   |
| Sex         | Passenger Gender                  |
| Age         | Passenger Age                     |
| Fare        | Ticket Fare                       |
| Embarked    | Port of Embarkation               |

### Dataset Statistics

* 📊 Total Records: **1000**
* 📋 Total Features: **7**

---

## 🛠 Technologies Used

* Python
* Google Colab
* Pandas
* NumPy
* Matplotlib
* Seaborn

---

## 🧹 Data Cleaning Process

To ensure high-quality analysis, the following preprocessing steps were performed:

✅ Dataset structure inspection

✅ Missing value identification

✅ Missing value treatment using median values

✅ Duplicate record removal

✅ Data consistency verification

---

## 📈 Key Performance Indicators (KPIs)

The dashboard generates the following metrics:

* 👥 Total Passengers
* 🛟 Total Survivors
* 📊 Survival Rate (%)
* 🎂 Average Passenger Age
* 💰 Average Ticket Fare

These KPIs provide a quick overview of passenger demographics and survival outcomes.

---

## 🎛 Interactive Features

Users can dynamically explore the dataset using:

* Gender-Based Filtering (Male / Female / All)
* Customized Visual Analysis
* Real-Time Insight Generation

---

## 📊 Dashboard Visualizations

### 1️⃣ Survival Distribution

A pie chart illustrating the proportion of passengers who survived versus those who did not.

### 2️⃣ Survival by Gender

A bar chart comparing survival rates between male and female passengers.

### 3️⃣ Survival by Passenger Class

A visualization showing how passenger class affected survival probability.

### 4️⃣ Age Distribution

A histogram representing the age spread of passengers aboard the Titanic.

### 5️⃣ Fare Distribution

A histogram highlighting the variation in ticket prices.

### 6️⃣ Age vs Fare Analysis

A scatter plot revealing the relationship between passenger age and ticket fare.

### 7️⃣ Embarkation Port Analysis

A count plot displaying passenger distribution across embarkation ports.

---

## 🔄 Project Workflow

```text
1. Upload Dataset
2. Load Data
3. Data Cleaning
4. KPI Calculation
5. Interactive Filtering
6. Visualization Generation
7. Insight Discovery
8. Conclusion & Reporting
```

---

## 💡 Key Insights

🔹 Survival rates varied significantly across passenger classes.

🔹 Female passengers generally showed higher survival probabilities.

🔹 Higher ticket fares often corresponded with higher-class passengers.

🔹 Most passengers belonged to adult age groups.

🔹 Passenger class played a major role in determining survival outcomes.

---

## ▶️ How to Run the Project

### Step 1: Open Google Colab

Create a new notebook in Google Colab.

### Step 2: Upload the Dataset

```python
from google.colab import files
uploaded = files.upload()
```

### Step 3: Import Required Libraries

```python
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns
```

### Step 4: Load the Dataset

```python
df = pd.read_csv("Titanic_AI_Dashboard.csv")
df.head()
```

### Step 5: Execute All Notebook Cells

Run the notebook sequentially to generate KPIs, filters, visualizations, and insights.

---

## 📁 Project Structure

```text
AI-Dashboard/
│
├── Titanic_AI_Dashboard.csv
├── AI_Dashboard.ipynb
├── README.md
└── screenshots/
```

---

## ✅ Results

The dashboard successfully delivers:

✔ Dataset Overview

✔ Data Cleaning & Preprocessing

✔ KPI Generation

✔ Interactive Filtering

✔ Multiple Visualizations

✔ Data-Driven Insights

✔ Exploratory Data Analysis

---

## 🎓 Conclusion

This project demonstrates how data analytics and visualization techniques can transform raw data into actionable insights. Through KPI monitoring, interactive filtering, and comprehensive visual analysis, the dashboard provides a deeper understanding of passenger demographics and survival trends aboard the Titanic.

The project serves as a practical example of dashboard development, exploratory data analysis, and data-driven storytelling using Python.

---

## 👨‍💻 Author

**Chintala Jaya Krishna**

**Project:** AI Dashboard – Titanic Passenger Survival Analysis

**Platform:** Google Colab

**Tools:** Python, Pandas, NumPy, Matplotlib, Seaborn
---
