# Seasonal Agriculture Performance Analysis

**AICTE Internship Program by Edunet Foundation — VOIS for Tech Program | Data Analytics**

A data analytics project focused on understanding how agricultural performance varies across India's three major cropping seasons — **Kharif, Rabi, and Zaid**.

The project analyzes agricultural, economic, environmental, water-resource, and disease/pest-related factors to identify meaningful patterns, compare seasonal performance, and generate data-driven recommendations for agricultural planning.

---

## 📌 Problem Statement

Agricultural performance is influenced by seasonal variations in weather conditions, soil characteristics, irrigation practices, resource usage, production costs, and disease or pest risks.

Raw agricultural data can make it difficult to understand how these factors affect farm performance across different seasons.

This project analyzes agricultural data to:

* Compare agricultural performance across Kharif, Rabi, and Zaid seasons.
* Identify seasonal patterns and trends.
* Analyze relationships between environmental conditions and agricultural outcomes.
* Evaluate crop-wise and state-wise performance.
* Study water consumption and irrigation efficiency.
* Investigate disease and pest risk.
* Identify unusual observations through outlier analysis.
* Statistically evaluate whether seasonal differences are significant.
* Develop evidence-based agricultural recommendations.

---

## 📂 Dataset

The project uses a dataset containing **4,000 agricultural records** covering farm-level information across **8 Indian states**.

### Dataset Categories

**🌱 Agricultural Information**

* Season
* Crop
* State
* Farm Area
* Yield
* Production

**💰 Economic Information**

* Revenue
* Cost
* Profit
* Price

**🌦️ Environmental Conditions**

* Rainfall
* Temperature
* Humidity
* Sunlight
* Soil Moisture
* Soil pH

**🚜 Farming Inputs & Resources**

* Irrigation Type
* Water Usage
* NPK
* Fertilizer
* Pesticide
* Seed Quality

**🐛 Risk Indicators**

* Disease/Pest Risk

---

## 🎯 Objectives

The major objectives of this project are:

1. Explore and understand the agricultural dataset.
2. Clean and prepare the data for analysis.
3. Compare agricultural performance across Kharif, Rabi, and Zaid.
4. Analyze seasonal trends in yield, production, revenue, cost, and profit.
5. Compare crop-wise and state-wise performance.
6. Analyze water usage and irrigation efficiency.
7. Study environmental factors affecting agricultural outcomes.
8. Investigate disease and pest risk across seasons.
9. Identify unusual observations using outlier analysis.
10. Perform statistical analysis using ANOVA.
11. Generate data-driven agricultural recommendations.

---

## 🛠️ Tech Stack

* **Python**
* **Google Colab**
* **Jupyter Notebook**
* **Pandas** — Data manipulation and analysis
* **NumPy** — Numerical computation
* **Matplotlib** — Data visualization
* **Seaborn** — Statistical visualization
* **SciPy** — Statistical analysis
* **Statistical Analysis**
* **Data Visualization**

---

## 🧹 Data Cleaning & Preparation

The dataset was systematically checked and prepared before analysis.

### Data Quality Checks

* Missing values
* Duplicate records
* Invalid numerical values
* Negative values
* Invalid soil pH values
* Data type consistency

### Data Cleaning

* Missing values were handled using **median imputation** where appropriate.
* Duplicate records were identified and removed.
* Numerical variables were validated for unreasonable or invalid values.
* Data types were standardized for analysis.

### Feature Engineering

Additional performance metrics were calculated to provide deeper insights:

* **Profit Margin**
* **Cost per Hectare**
* **Revenue per Hectare**
* **Profit per Hectare**
* **Water Efficiency**

These metrics helped evaluate agricultural performance beyond basic yield and production figures.

---

# 📊 Analysis Performed

## 🌦️ Seasonal Analysis

Agricultural performance was compared across:

* **Kharif**
* **Rabi**
* **Zaid**

The following metrics were analyzed:

* Average Yield
* Production
* Revenue
* Cost
* Profit
* Water Usage
* Water Efficiency
* Disease/Pest Risk

---

## 🌱 Crop-wise Analysis

Crop performance was analyzed across different seasons to identify:

* High-performing crops
* Seasonal variations in crop performance
* Differences in yield and profitability
* Crop-specific opportunities and challenges

---

## 🗺️ State-wise Analysis

Agricultural performance was compared across different Indian states.

The analysis focused on:

* Yield
* Production
* Revenue
* Cost
* Profit
* Seasonal performance
* Regional differences

This helps identify geographical variations in agricultural outcomes.

---

## 💧 Irrigation & Water Analysis

Water usage and irrigation conditions were analyzed to understand resource efficiency.

Key areas include:

* Water consumption
* Irrigation type
* Water efficiency
* Seasonal water requirements
* Relationship between water usage and yield

Special attention was given to the **Zaid season**, which showed relatively high water consumption and lower water efficiency.

---

## 🌦️ Environmental Analysis

The project investigates the relationship between agricultural performance and environmental factors, including:

* Rainfall
* Temperature
* Humidity
* Sunlight
* Soil Moisture
* Soil pH

These factors were analyzed to understand their potential relationship with yield, production, profitability, and other agricultural outcomes.

---

## 📈 Correlation Analysis

Correlation analysis was performed to investigate relationships between:

* Agricultural variables
* Environmental conditions
* Resource usage
* Economic outcomes

This helped identify variables that move together and provided insights into potential relationships within the dataset.

> **Note:** Correlation indicates association, not causation.

---

## 📦 Outlier Analysis

The **Interquartile Range (IQR)** method was used to identify unusual yield observations.

Outlier analysis helps determine whether extreme observations may represent:

* Exceptional agricultural performance
* Unusual farming conditions
* Data-quality issues
* Potentially important cases requiring further investigation

---

# 📊 Statistical Analysis

## ANOVA — Seasonal Yield

One-way ANOVA was performed to determine whether average yield differs significantly across the three agricultural seasons.

* **F-statistic:** 1.54
* **p-value:** 0.214

Since the p-value is greater than **0.05**, the analysis did **not find statistically significant evidence of a difference in average yield across the three seasons**.

---

## ANOVA — Seasonal Profit

One-way ANOVA was also performed for profit.

* **F-statistic:** 34.29
* **p-value:** < 0.001

The result indicates that **profit differs significantly across seasons**.

This highlights an important finding: seasonal differences may be much more evident in **economic performance** than in average yield alone.

---

# 💡 Recommendations

Based on the analysis, the following recommendations were developed:

### 1. Improve Seasonal Planning

Agricultural planning should consider seasonal differences in profitability, yield, resource requirements, and environmental conditions.

### 2. Optimize Zaid Water Management

Zaid showed relatively high water usage and lower water efficiency. Improved irrigation planning and water-efficient practices could help reduce resource wastage.

### 3. Use Season-Specific Crop Selection

Crop selection should consider the expected yield, profitability, resource requirements, and seasonal suitability of each crop.

### 4. Consider Regional Differences

State-wise differences should be incorporated into agricultural planning rather than applying the same strategy across all regions.

### 5. Strengthen Disease & Pest Monitoring

Higher-risk seasons and crops should receive greater monitoring and preventive attention.

### 6. Focus on Profitability, Not Only Yield

Agricultural decisions should consider **profit, cost, revenue, and resource efficiency** in addition to yield.

### 7. Investigate Outliers

Unusual observations should be examined to determine whether they represent genuine exceptional performance or potential data-quality problems.

---

# 📌 Business & Agricultural Insights

The analysis highlights several important insights:

* **Highest yield does not necessarily mean highest profitability.**
* Seasonal conditions have a stronger observed impact on **profitability** than on average yield in this dataset.
* **Kharif** showed the strongest overall economic performance.
* **Zaid** requires greater attention to water management and profitability.
* Water efficiency can be an important metric for evaluating agricultural sustainability.
* State and crop-level differences should be considered when making agricultural decisions.
* Statistical analysis provides additional evidence beyond visual comparisons.

---

# 📁 Project Structure

```text
Seasonal-Agriculture-Performance-Analysis/
│
├── Seasonal_Agriculture_Performance_Analysis.ipynb
├── seasonal_agriculture_performance_dataset.csv
├── README.md
│
└── visuals/
```

---

# ▶️ How to Run

## Using Google Colab

1. Download the `Seasonal_Agriculture_Performance_Analysis.ipynb` notebook.
2. Open **Google Colab**.
3. Select **File → Upload notebook**.
4. Upload the `.ipynb` file.
5. Upload `seasonal_agriculture_performance_dataset.csv` when required.
6. Run the notebook cells sequentially.

## Required Libraries

```python
pandas
numpy
matplotlib
seaborn
scipy
```

You can install missing libraries using:

```python
!pip install pandas numpy matplotlib seaborn scipy
```

---

# 📓 Notebook Contents

The Jupyter Notebook contains the complete analysis workflow:

1. Project Introduction
2. Importing Libraries
3. Loading the Dataset
4. Dataset Overview
5. Exploratory Data Analysis
6. Data Quality Checks
7. Data Cleaning
8. Feature Engineering
9. Seasonal Analysis
10. Crop-wise Analysis
11. State-wise Analysis
12. Irrigation Analysis
13. Environmental Analysis
14. Correlation Analysis
15. Outlier Analysis
16. Statistical Analysis — ANOVA
17. Key Findings
18. Recommendations
19. Final Conclusion

---

# 📜 Internship Context

This project was developed as part of the:

**AICTE Internship Program by Edunet Foundation**
**VOIS for Tech Program — Data Analytics**

The project demonstrates practical application of Python-based data analytics, exploratory data analysis, visualization, statistical analysis, and data-driven decision-making on an agricultural dataset.

---

# 👩‍💻 Author

**Divya Jain**

**Data Analytics Project | Python | Pandas | Data Visualization | Statistical Analysis**

---

## ⭐ Project Highlights

* **4,000+ agricultural records**
* **8 Indian states**
* **3 agricultural seasons**
* Seasonal performance analysis
* Crop-wise analysis
* State-wise analysis
* Water efficiency analysis
* Environmental analysis
* Correlation analysis
* Outlier detection
* ANOVA statistical testing
* Data-driven recommendations

---

⭐ **If you find this project useful, consider giving the repository a star!**
