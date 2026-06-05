# 🚢 Titanic Exploratory Data Analysis (EDA)

## 📌 Project Overview

This project performs **Exploratory Data Analysis (EDA)** on the Titanic dataset using Python. The objective is to understand passenger characteristics, identify important patterns, analyze survival trends, and uncover relationships between various features that influenced survival during the Titanic disaster.

Through statistical summaries and visualizations, the analysis explores factors such as gender, passenger class, age, fare, and embarkation port to gain meaningful insights from the dataset.

---

## 🎯 Objectives

- Understand the structure and quality of the dataset.
- Identify missing values and data inconsistencies.
- Analyze passenger demographics such as age and gender.
- Examine the relationship between passenger class, fare, and survival.
- Identify trends, correlations, and outliers using visualizations.
- Generate meaningful insights from the Titanic dataset.

---

## 📂 Dataset Information

The Titanic dataset contains passenger information such as:

- Passenger Class
- Gender
- Age
- Fare
- Family Information
- Embarkation Port
- Survival Status

### Files Included

| File | Description |
|--------|------------|
| `train.csv` | Dataset used for Exploratory Data Analysis |
| `test.csv` | Dataset used for prediction tasks (not used in this project) |
| `gender_submission.csv` | Sample prediction submission file |

### Why Only `train.csv`?

The `train.csv` dataset contains the target variable **Survived**, which indicates whether a passenger survived (`1`) or did not survive (`0`) the disaster.

Since this project focuses on Exploratory Data Analysis rather than predictive modeling, `train.csv` is sufficient for performing the analysis.

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Google Colab

---

## 📊 Exploratory Data Analysis Performed

### Data Understanding

- Dataset Shape Analysis
- Data Types Inspection
- Statistical Summary
- Feature Understanding

### Data Quality Assessment

- Missing Value Analysis
- Duplicate Record Detection
- Data Structure Validation

### Univariate Analysis

- Survival Distribution
- Gender Distribution
- Passenger Class Distribution
- Age Distribution
- Fare Distribution
- Embarkation Port Distribution

### Bivariate Analysis

- Survival by Gender
- Survival by Passenger Class
- Survival by Embarkation Port
- Age vs Fare Analysis

### Multivariate Analysis

- Correlation Heatmap
- Pairplot Analysis

---

## 📈 Key Visualizations

### Survival Count Plot
Analyzes the distribution of survivors and non-survivors.

### Survival by Gender
Compares survival outcomes across male and female passengers.

### Survival by Passenger Class
Examines how passenger class influenced survival rates.

### Age Distribution Histogram
Shows the age distribution of passengers.

### Fare Distribution Histogram
Visualizes ticket fare distribution and skewness.

### Fare Boxplot
Identifies fare outliers.

### Correlation Heatmap
Displays relationships among numerical variables.

### Pairplot Analysis
Provides a comprehensive view of relationships among multiple variables.

### Age vs Fare Scatter Plot
Explores the relationship between passenger age and ticket fare.

---

## 🔍 Key Findings

- Female passengers had significantly higher survival rates than male passengers.
- First-Class passengers experienced the highest survival rates.
- Passenger Class and Fare were the strongest factors associated with survival.
- Most passengers were between 20 and 40 years of age.
- The Fare distribution was highly right-skewed and contained several outliers.
- Southampton was the primary embarkation port for most passengers.
- Missing values were mainly concentrated in the Cabin and Age columns.

---

## 📊 Dataset Insights

| Metric | Value |
|----------|---------|
| Total Passengers | 891 |
| Total Features | 12 |
| Survived | 342 |
| Did Not Survive | 549 |
| Female Survival Rate | 74.20% |
| Male Survival Rate | 18.89% |
| First Class Survival Rate | 62.96% |
| Second Class Survival Rate | 47.28% |
| Third Class Survival Rate | 24.24% |

---

## 📁 Project Structure

```text
Titanic-Exploratory-Data-Analysis/
│
├── train.csv
├── test.csv
├── gender_submission.csv
├── Titanic_Exploratory_Data_Analysis.ipynb
├── Titanic Exploratory Data Analysis.pdf
├── README.md
│
├── Screenshots/
│   ├── Age_Boxplot.png
│   ├── Age_Distribution.png
│   ├── Age_VS_Fare_ScatterPlot.png
│   ├── Correlation_Heatmap.png
│   ├── Dataset_Information.png
│   ├── Dataset_Preview.png
│   ├── Dataset_Statistics.png
│   ├── Embarked_Distribution.png
│   ├── Embarked_Distribution_Visualization.png
│   ├── Fare_Boxplot.png
│   ├── Fare_Distribution.png
│   ├── Final_Summary.png
│   ├── Gender_Distribution.png
│   ├── Gender_Distribution_Visualization.png
│   ├── InterviewQ&A.png
│   ├── Missing_Values.png
│   ├── Pairplot_Analysis.png
│   ├── Passenger_Class_Distribution.png
│   ├── Passenger_Class_Visualization.png
│   ├── Survival_by_Embarked.png
│   ├── Survival_by_Gender.png
│   ├── Survival_by_Passenger_Class.png
│   ├── Survival_Count.png
│   └── Survival_Count_Visualization.png
```

---

## ✅ Conclusion

This Exploratory Data Analysis project successfully identified important factors influencing passenger survival. The analysis revealed that **Gender, Passenger Class, and Fare** were the most significant variables affecting survival outcomes.

EDA helped uncover meaningful patterns, identify missing values and outliers, and understand relationships within the dataset, demonstrating the importance of data exploration before applying machine learning techniques.

---

## 👨‍💻 Author

**Abhishek Savita**

GitHub: https://github.com/Abhishek-Savita-3012
