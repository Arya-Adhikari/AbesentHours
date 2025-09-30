# Employee Absenteeism Analysis

This project explores employee absenteeism data to uncover patterns and insights that can help organizations understand workforce behavior. The analysis includes data cleaning, exploratory data analysis (EDA), visualizations, and statistical tests.

---

## 📊 Project Overview

* **Dataset**: `MFGEmployees4.csv`
* **Objective**: Analyze absenteeism patterns across demographics, job roles, departments, store locations, and divisions.
* **Techniques Used**:

  * Data cleaning & preprocessing
  * Outlier detection and removal (IQR method)
  * Feature engineering (job title standardization, job category mapping, gender encoding, age grouping)
  * Exploratory data analysis (EDA) with visualizations
  * Statistical hypothesis testing (t-test & ANOVA)

---

## 🛠️ Tools & Libraries

* **Python**
* **Pandas** – data manipulation
* **NumPy** – numerical operations
* **Matplotlib & Seaborn** – static visualization
* **Plotly Express** – interactive visualization
* **SciPy** – statistical analysis
* **Statsmodels** – post-hoc testing (Tukey HSD, if extended)

---

## 📂 Project Structure

```
├── data/
│   └── MFGEmployees4.csv     # Raw dataset
├── notebooks/
│   └── absenteeism_analysis.ipynb   # Jupyter Notebook with analysis
├── README.md
└── requirements.txt          # Dependencies
```

---

## 🔍 Analysis Highlights

1. **Data Quality Check**: Missing values, duplicates, outliers
2. **EDA & Visualization**:

   * Average Absent Hours by Gender
   * Employee Composition by City (Top 10)
   * Total Absent Hours by Job Title & Department
   * Absenteeism across Age Groups, Store Locations, Divisions
   * Correlation Heatmap (Age, Length of Service, Absent Hours)
3. **Statistical Tests**:

   * **t-test** → Gender differences in absenteeism
   * **ANOVA** → Differences across Division, Department, Job Titles, etc.
4. **Data Cleaning & Feature Engineering**:

   * Standardized job titles
   * Grouped into job categories (HR, Finance, Legal, Retail, etc.)
   * Encoded categorical features for analysis

---

## 🚀 How to Run

1. Clone this repository:

   ```bash
   git clone https://github.com/yourusername/employee-absenteeism.git
   cd employee-absenteeism
   ```
2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```
3. Run the analysis:

   ```bash
   jupyter notebook notebooks/absenteeism_analysis.ipynb
   ```

---

## 📈 Future Improvements

* Build predictive models to classify/predict absenteeism risk
* Add effect sizes and post-hoc tests for deeper statistical insights
* Interactive dashboards using Plotly or Power BI

---

## 📝 Author

Developed by **Arya Adhikari**
