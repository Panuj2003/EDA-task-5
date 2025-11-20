# Task 5 – Exploratory Data Analysis (EDA) 

This project performs Exploratory Data Analysis (EDA) on the Titanic dataset (train.csv).  
The aim of the task is to clean the data, analyze patterns, visualize relationships, and summarize key insights.

##  Steps Performed

### 1. Data Loading
 Loaded the Titanic train dataset using Pandas.
 Displayed first few rows to understand structure.

### 2. Data Cleaning
 Checked missing values using `df.info()` and `df.isnull().sum()`.
 Filled missing Age values using median.
 Filled missing Embarked values using mode.
 Dropped Cabin column due to too many missing values (687).

### 3. Univariate Analysis
 Countplot of Survived
 Countplot of Sex
 Histogram of Age
 Histogram of Fare

### 4. Bivariate Analysis
 Survived vs Sex
 Survived vs Pclass
 Boxplots of Age vs Survived
 Boxplots of Fare vs Survived

### 5. Correlation & Pairplot
 Heatmap of numeric features
 Pairplot of Age, Fare, Pclass, Survived

### 6. Observations
 Females had higher survival rate.
 1st class passengers survived more than 2nd & 3rd class.
 Younger passengers had slightly better survival.
 Higher fare passengers had higher survival chances.
 Survived shows:
   Positive correlation with Fare
   Negative correlation with Pclass

### 7. Final Summary
 Survival strongly depended on gender, class, and fare.
 Women, children, and wealthy passengers had better chances of survival.

##  Files Included
 `EDA.ipynb` – Jupyter Notebook with full analysis  
 `EDA.pdf` – PDF Export of notebook  
 `train.csv` – Dataset used  
 `README.md` – Project documentation  

##  How to Run
 Install required libraries:
 Jupyter notebook
 Pandas
 seaborn
 Matplotlip
 NumPy
 
