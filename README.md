#### 🚢 Titanic Dataset Analysis 
📌 Overview
This project explores the famous Titanic dataset using Python, Pandas, Seaborn, and Matplotlib.
The goal is to perform Exploratory Data Analysis (EDA), clean missing values, and uncover insights about passenger survival patterns.

----

### 📂 Dataset Information
## Rows: 891

## Columns: 12

Features: Passenger demographics, ticket details, fare, cabin, and survival status.

## Key columns:

Survived → Survival status (0 = No, 1 = Yes)

Pclass → Passenger class (1st, 2nd, 3rd)

Sex → Gender

Age → Age in years

Fare → Ticket fare

Embarked → Port of embarkation

### 🛠️ Steps Performed
Data Loading → Imported CSV using Pandas.

Data Cleaning →

Dropped Cabin (too many missing values).

Filled missing Age with mean.

Converted Age to integer type.

Exploratory Data Analysis (EDA) →

Gender distribution

Survival analysis by gender, class, and age groups

Fare distribution and anomalies

## Visualization →

Pie charts for gender, age groups, and survival rates

Bar plots for survival counts

Heatmap for correlation analysis

### 📊 Key Insights
## Gender:

Males: 577 (64.8%)

Females: 314 (35.2%)

Survival: 233 females vs 109 males

## Class:

1st Class survival rate: 63%

2nd Class survival rate: 47%

3rd Class survival rate: 24%

## Age Groups:

Children (<20): Survival rate 45.9%

Adults (20–40): Survival rate 36.3%

Seniors (40+): Survival rate 36.7%

## Fare:

Average fare: ₹32.20

15 passengers had zero fare tickets.

### 🔥 Visualizations
📌 Gender distribution pie chart

📌 Survival by gender bar chart

📌 Survival rates by class pie charts

📌 Age distribution pie chart

📌 Correlation heatmap

📌 Fare histogram & boxplot

### 🚀 Tech Stack
Python 🐍

Pandas → Data manipulation

Seaborn & Matplotlib → Visualization

### 📈 Future Work
Build predictive models (Logistic Regression, Random Forest).

Feature engineering (family size, title extraction from names).

Compare survival predictions with actual outcomes.

### 🙌 Acknowledgements
## Dataset: Kaggle Titanic Dataset  
## Inspired by classic machine learning problem: “Predict survival on the Titanic.”
