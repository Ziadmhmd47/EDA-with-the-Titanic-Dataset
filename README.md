# Titanic Dataset - Exploratory Data Analysis (EDA)

## 📌 Project Overview

This project performs Exploratory Data Analysis (EDA) on the Titanic dataset to understand the data, identify missing values, detect outliers, discover patterns, and prepare features for future Machine Learning tasks.

The main goal is to explore the dataset, improve data quality, and extract meaningful insights through statistical analysis and visualization.

## 🎯 Project Objectives

- Understand the dataset structure and features.
- Identify and handle missing values.
- Detect and analyze duplicate records.
- Perform data cleaning and preprocessing.
- Apply Feature Engineering.
- Explore relationships between different features.
- Analyze correlations between numerical features.
- Detect and handle outliers.
- Apply feature scaling techniques.
- Extract meaningful insights from the data.

## 🛠️ Tools & Libraries

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook

## 📊 Project Workflow

### 1. Data Inspection
- Dataset overview.
- Data types and structure.
- Descriptive statistics.

### 2. Data Cleaning
- Missing values detection.
- Handling missing values.
- Duplicate detection.
- Removing unnecessary columns.

### 3. Feature Engineering
- Encoding categorical features.
- Creating `FamilySize`.
- Creating `IsAlone`.

### 4. Exploratory Data Analysis
- Univariate Analysis.
- Bivariate Analysis.
- Data Visualization.
- Survival Analysis.
- Correlation Analysis.

### 5. Outlier Detection & Treatment
Applied three outlier detection methods:

- Interquartile Range (IQR).
- Standard Deviation.
- Z-Score.

Used IQR-based Capping to handle extreme Fare values.

### 6. Feature Scaling

Applied two feature scaling techniques:

- Standardization.
- Normalization.

## 🔍 Key Findings

- The dataset contains 891 rows and 12 columns.
- The overall survival rate was approximately 38.38%.
- Female passengers had a significantly higher survival rate (74.20%) than male passengers (18.89%).
- Cabin had a high percentage of missing values (77.10%).
- Age contained 177 missing values.
- Embarked contained only 2 missing values.
- Family-related features provided useful insights into passenger survival.

## 📁 Repository Structure

```text
Titanic-EDA/
│
├── EDA.ipynb
├── README.md
└── requirements.txt
```

## ⚙️ Installation & Usage

1. Clone the repository:

```bash
git clone https://github.com/YOUR_USERNAME/Titanic-EDA.git
```

2. Navigate to the project directory:

```bash
cd Titanic-EDA
```

3. Install the required libraries:

```bash
pip install -r requirements.txt
```

4. Open the notebook:

```bash
jupyter notebook EDA.ipynb
```

## 📌 Important Note

The preprocessing steps in this notebook are performed for exploratory and educational purposes.

For future Machine Learning models, preprocessing operations such as imputation, outlier treatment, and scaling should be fitted using training data only to prevent data leakage.

## 👨‍💻 Author

**Ziad Mohamed**

Computer Science Student | AI Enthusiast

GitHub: [Ziadmhmd47](https://github.com/Ziadmhmd47)
