# 🚢 Titanic Exploratory Data Analysis (EDA)

## Project Overview

This project is an Exploratory Data Analysis (EDA) of the famous Titanic dataset. The goal is to uncover patterns, insights, and relationships within the data to understand the factors that contributed to the survival or non-survival of passengers aboard the RMS Titanic.

The analysis focuses on exploring distributions, correlations, and feature engineering to prepare the data for potential future machine learning modeling.

## Key Files

| File Name | Description |
| :--- | :--- |
| `titanic_eda.ipynb` | The main Jupyter Notebook containing the full Exploratory Data Analysis, visualizations, data cleaning, and feature engineering. |
| `train.csv` | The primary dataset used for this analysis. It contains passenger information and the 'Survived' target variable. |
| `README.md` | This file, providing an overview of the project. |

## Analysis Goals

The EDA in the `titanic_eda.ipynb` notebook covers:

1.  **Data Loading & Initial Inspection:** Checking for missing values, data types, and unique values.
2.  **Missing Value Imputation:** Handling missing values in columns like `Age`, `Cabin`, and `Embarked`.
3.  **Univariate Analysis:** Analyzing the distribution of individual features (e.g., `Age`, `Fare`, `Pclass`).
4.  **Bivariate Analysis:** Exploring the relationship between individual features and the target variable, `Survived` (e.g., survival rate by `Sex`, `Pclass`, and `Embarked`).
5.  **Feature Engineering:** Creating new features (e.g., `FamilySize`, `Title`) from existing ones to capture more predictive information.
6.  **Data Visualization:** Using charts and plots to present key findings.

## Key Findings (Summary)


* **Gender Bias:** Females had a significantly higher survival rate than males.
* **Socio-economic Status:** Passengers in **First Class (Pclass=1)** had the highest chance of survival, indicating class played a major role.
* **Age Factor:** Children (especially those under 10) had a higher survival rate compared to older passengers, reflecting the "women and children first" protocol.
* **Family Size:** Passengers traveling alone or with a medium-sized family (2-4 members) had better survival odds than those with very large families.

## Technologies and Libraries

This project is implemented in Python and utilizes the following libraries:

* **Python 3.x**
* **VS code** (for the analysis environment)
* `pandas` (for data manipulation and analysis)
* `numpy` (for numerical operations)
* `matplotlib` (for basic plotting)
* `seaborn` (for statistical data visualization)

You can also view the notebook directly on GitHub or platforms like **Google Colab** without needing a local setup.


## 👩‍💻 Author
**Aditi K**  
CSE (AI & ML) | Titanic | EDA 
