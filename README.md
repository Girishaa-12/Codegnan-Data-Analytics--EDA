# 📊 Adult Income Dataset – Exploratory Data Analysis

## 📌 Project Overview

This project performs **Exploratory Data Analysis (EDA)** on the Adult Income dataset using Python. The analysis focuses on understanding the dataset, performing statistical analysis, handling missing values, detecting outliers, and creating visualizations to identify patterns and relationships within the data.

## 🎯 Objectives

* Explore the structure and characteristics of the dataset
* Analyze numerical and categorical variables
* Perform statistical analysis
* Identify and handle missing values
* Detect outliers using statistical techniques
* Analyze income and education-related patterns
* Create visualizations for better understanding of the data

## 🛠️ Tools & Technologies

* **Python**
* **Pandas** – Data manipulation and analysis
* **NumPy** – Numerical operations
* **Matplotlib** – Data visualization
* **Seaborn** – Statistical visualization
* **Plotly** – Interactive visualization
* **SciPy** – Statistical analysis
* **YData Profiling** – Automated EDA
* **Jupyter Notebook / Google Colab**

## 🔍 Analysis Performed

### 1. Data Exploration

* Displayed the first and last records
* Checked dataset shape
* Examined data types
* Inspected indexes and values
* Analyzed unique and distinct values
* Examined categorical columns such as:

  * Workclass
  * Education
  * Occupation
  * Income
  * Native Country

### 2. Statistical Analysis

Calculated:

* Mean
* Median
* Minimum
* Maximum
* Standard deviation
* Correlation
* Frequency distributions

The analysis also examined **age, hours-per-week, capital-gain, and capital-loss**.

### 3. Data Cleaning

The notebook includes techniques for:

* Identifying missing values
* Replacing `?` values with missing values
* Filling missing values
* Mean-based imputation
* Median-based imputation
* Mode-based imputation
* Removing rows containing missing values
* Removing unnecessary columns

### 4. Outlier Detection

Outliers were explored using:

* **IQR (Interquartile Range)**
* **Z-Score**

Winsorization was also applied to demonstrate an outlier-treatment technique.

### 5. Data Visualization

Visualizations created in the project include:

* Age distribution histogram
* Education distribution pie chart
* Scatter plot
* Statistical visualizations using Matplotlib, Seaborn and Plotly

### 6. Automated EDA

The project also explores automated EDA tools such as:

* AutoViz
* Sweetviz
* D-Tale
* YData Profiling

## 📁 Project Structure

```text
Adult-Income-EDA/
│
├── EDA_project1.ipynb
├── README.md
└── dataset/
    └── adult_income.csv
```

> Replace `adult_income.csv` with the actual dataset filename if it is different.

## 📈 Key Areas Analyzed

The analysis mainly focuses on the relationship between:

* Age and Income
* Education and Income
* Education and Population Distribution
* Working Hours and Income
* Capital Gain and Capital Loss
* Workclass and Occupation
* Numerical variable relationships

## 🚀 How to Run

1. Clone or download this repository.
2. Open **"EDA_project1.ipynb"** using Jupyter Notebook or Google Colab.
3. Place the dataset in the required location.
4. Run the notebook cells sequentially.

## 💡 Skills Demonstrated

**Python | Pandas | NumPy | Matplotlib | Seaborn | Plotly | SciPy | Data Cleaning | Exploratory Data Analysis | Statistical Analysis | Data Visualization | Outlier Detection | Missing Value Handling**

## 👤 Author

**Girisha Thangavalu**

B.Tech – Computer Science & Engineering (Data Science)
