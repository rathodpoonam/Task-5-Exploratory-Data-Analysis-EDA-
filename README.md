# Titanic Dataset - Exploratory Data Analysis (EDA)

## 📌 Project Overview
This project performs **Exploratory Data Analysis (EDA)** on the famous **Titanic dataset** from Kaggle.  
The goal is to analyze passenger data, identify trends, patterns, and relationships, and gain insights about survival rates.

The EDA is performed using **Python** with `pandas`, `matplotlib`, and `seaborn`.

---

## 📂 Dataset
**Source:** [Kaggle - Titanic Dataset](https://www.kaggle.com/c/titanic/data)  
File used: `train.csv`  

**Main Columns:**
- `PassengerId`: Unique passenger ID  
- `Survived`: Survival status (0 = No, 1 = Yes)  
- `Pclass`: Ticket class (1 = 1st, 2 = 2nd, 3 = 3rd)  
- `Name`: Passenger name  
- `Sex`: Gender  
- `Age`: Age in years  
- `SibSp`: # of siblings/spouses aboard  
- `Parch`: # of parents/children aboard  
- `Ticket`: Ticket number  
- `Fare`: Ticket fare  
- `Cabin`: Cabin number  
- `Embarked`: Port of embarkation (C = Cherbourg, Q = Queenstown, S = Southampton)  

---

## 🛠 Tools & Libraries
- **Python**
- **pandas** → Data manipulation & cleaning  
- **matplotlib** → Data visualization  
- **seaborn** → Statistical plots  

---

## 🔍 Steps Performed
1. **Data Loading & Basic Exploration**
   - Loaded dataset and checked structure using `.info()` and `.describe()`
   - Identified missing values

2. **Univariate Analysis**
   - Count plots for categorical variables
   - Histograms for numerical variables

3. **Bivariate Analysis**
   - Survival rate by gender and class
   - Age distribution across survival status
   - Fare distribution by survival

4. **Multivariate Analysis**
   - Correlation heatmap
   - Pairplot for selected features

5. **Missing Value Handling**
   - Filled `Age` with median value
   - Filled `Embarked` with mode value

6. **Insights Summary**
   - Females had a higher survival rate than males
   - 1st class passengers had the highest survival rate
   - Younger passengers had better survival chances
   - Higher fare correlated with survival

---

## 📊 Example Visuals
- Survival rate by gender
- Age distribution of passengers
- Correlation heatmap
- Fare distribution by survival
