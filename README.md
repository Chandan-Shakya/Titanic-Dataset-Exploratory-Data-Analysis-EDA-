# 🚢 Titanic Dataset Exploratory Data Analysis (EDA)

## 📖 Project Overview
This project performs a detailed **Exploratory Data Analysis (EDA)** on the famous **Titanic dataset**.  
The Titanic dataset is widely used for data analysis and machine learning practice.  
The goal of this project is to explore the dataset, clean missing values, and find patterns, trends, and insights related to passenger survival.  

---

## 📊 Dataset Information
- Number of passengers: 891
- Features include:
  - **Passenger information**: Age, Gender, Class, Fare, Embarked, etc.
  - **Target variable**: Survived (1 = Yes, 0 = No)

---

## 🧹 Data Cleaning
- **Age** → 177 missing values → filled with median age.  
- **Embarked** → 2 missing values → filled with mode (Southampton).  
- **Embark_town** → 2 missing values → filled with mode (Southampton).  
- **Deck** → 688 missing values → column dropped due to high missing percentage.  

---

## 🔍 Exploratory Data Analysis (EDA)

### 1. Univariate Analysis
- **Age distribution**: Most passengers were 20–40 years old.  
- **Gender distribution**: More male passengers than female.  
- **Passenger class**: Most passengers were in 3rd class.  

### 2. Bivariate Analysis
- **Survival by Gender** → Females had a much higher survival rate.  
- **Survival by Class** → First-class passengers survived the most, third-class the least.  
- **Survival by Age** → Children and younger passengers had higher chances of survival.  
- **Fare vs Survival** → Passengers who paid higher fares had better survival chances.  

### 3. Correlation Analysis
- **Survival is positively correlated with Fare.**  
- **Survival is negatively correlated with Passenger Class.**  
- Age has a weak correlation with survival.  

---

## 📈 Visualizations
- Countplots for categorical variables (Gender, Class, Embarked).  
- Histograms for numerical variables (Age, Fare).  
- Boxplots to compare Age and Fare with Survival.  
- Heatmap for correlation analysis.  

---

## 📝 Insights
1. **Women and children were prioritized** during rescue (higher survival).  
2. **First-class passengers** had the best survival chances, reflecting social class advantage.  
3. **Fare amount** was directly related to survival chances.  
4. **Third-class male passengers** had the lowest survival rate.  

---

## ⚙️ Requirements
To run this notebook, install:



---

✅ With this `README.md`, your GitHub repo will look **structured and professional**.  

👉 Do you want me to also **write the GitHub commit message + description** so you can directly upload with the right text?

```bash
pip install pandas numpy seaborn matplotlib
