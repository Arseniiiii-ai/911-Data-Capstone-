# 911 Calls Data Capstone Project

This project analyzes 911 emergency call data to identify patterns, trends, and insights using data analysis and visualization techniques in Python.

---

## 🧠 Project Overview

Emergency call datasets provide valuable information about incident types, timing, and frequency.  
In this capstone project, the data is explored and visualized to answer key questions such as:

- When do emergency calls peak?
- What types of emergencies are most common?
- How do call patterns change over time?

---

## 📁 Project Structure

911-Data-Capstone-/
├── Data/ # Raw and processed datasets
├── Src/ # Jupyter notebooks with analysis and modeling
├── Visuals/ # Generated plots and visual outputs
└── README.md # Project documentation

---

## 📓 Notebooks Description (Src)

Each notebook in the `Src/` folder focuses on a specific stage of the analysis.

### 1️⃣ Data Cleaning & Preparation
- Loads raw 911 call data from the `Data/` folder
- Handles missing values
- Converts timestamps to datetime format
- Creates new time-based features (hour, day, month)

### 2️⃣ Exploratory Data Analysis (EDA)
- Analyzes call volume by hour, day, and month
- Examines the distribution of emergency call reasons
- Identifies trends and seasonal patterns
- Compares different emergency categories

### 3️⃣ Data Visualization
- Line plots showing call trends over time
- Count plots for emergency types
- Heatmaps for call frequency by day and hour
- All plots are saved into the `Visuals/` folder

### 4️⃣ (Optional) Modeling / Forecasting
- Prepares data for basic predictive analysis
- Demonstrates how modeling can be applied to time-based call data
- Focuses on concept demonstration rather than production accuracy

---

## 📸 Example Outputs (Visuals)

The `Visuals/` folder contains example outputs such as:

- 📈 **Time-series plots** of total 911 calls over time  
- 🕒 **Heatmaps** showing peak call hours and days  
- 📊 **Bar charts** comparing EMS, Fire, and Traffic calls  
- 📉 **Trend visualizations** highlighting seasonal effects  

These visualizations help quickly understand emergency call behavior.

---

## 🛠️ Technologies Used

- **Python**
- **pandas** – data manipulation  
- **numpy** – numerical analysis  
- **matplotlib & seaborn** – visualization  

---

## 🚀 How to Run the Project

1. Clone the repository:
   ```bash
   git clone https://github.com/Arseniiiii-ai/911-Data-Capstone-.git
