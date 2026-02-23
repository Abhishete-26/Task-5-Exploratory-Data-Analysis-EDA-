# 🚢 Titanic Dataset - Exploratory Data Analysis (EDA)

## 📌 Project Objective
The objective of this project is to perform Exploratory Data Analysis (EDA) on the Titanic dataset to identify patterns, trends, and factors that influenced passenger survival.

---

## 🛠 Tools & Technologies Used
- Python
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook (VS Code)

---

## 📂 Dataset Information
Source: Kaggle Titanic Dataset  
File used: `train.csv`

The dataset includes passenger details such as:
- PassengerId
- Survived
- Pclass
- Name
- Sex
- Age
- Fare
- Embarked
- and more

---

## 🔎 Steps Performed

1. Imported necessary libraries.
2. Loaded and inspected the dataset using:
   - `.info()`
   - `.describe()`
   - `.value_counts()`
   - `.isnull().sum()`
3. Performed Univariate Analysis:
   - Histograms
   - Countplots
4. Performed Bivariate Analysis:
   - Survival vs Gender
   - Survival vs Passenger Class
   - Scatterplots
5. Generated Correlation Heatmap.
6. Created Pairplot to identify relationships.
7. Documented observations for each visualization.
8. Summarized key findings.

---

## 📊 Key Insights

- Female passengers had a significantly higher survival rate than males.
- 1st class passengers survived more compared to 3rd class.
- Higher fare increased survival probability.
- Passenger class and gender were strong survival indicators.
- Some missing values were observed in Age and Cabin columns.

---

## 📁 Project Files

- `Task5_EDA_Titanic.ipynb` – Jupyter Notebook with complete analysis
- `Task5_EDA_Titanic_Report.pdf` – Exported report
- `README.md` – Project documentation

---

## ✅ Conclusion

This analysis demonstrates how data visualization and statistical exploration help in discovering meaningful insights and survival patterns from historical datasets.

---

⭐ If you found this project useful, feel free to explore and learn!
