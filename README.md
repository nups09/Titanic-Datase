
# 🧠 Task 5 – Exploratory Data Analysis (EDA) | Data Analyst Internship

## 📁 Project Title:
**Exploratory Data Analysis on Titanic Dataset using Python (Pandas, Seaborn, Matplotlib)**

---

## 🎯 Objective:
The aim of this project is to apply Exploratory Data Analysis (EDA) techniques to extract meaningful insights from the Titanic dataset using various statistical and visualization methods.

---

## 📌 Tools & Libraries Used:
- Python 3.x
- Jupyter Notebook
- Pandas
- Matplotlib
- Seaborn

---

## 📊 Dataset:
**Source:** [Kaggle Titanic Dataset](https://www.kaggle.com/c/titanic/data?select=train.csv)  
**File Used:** `train.csv`  
The dataset contains information about Titanic passengers including age, sex, ticket class, fare, and survival status.

---

## 📈 Key Steps Performed:

1. **Data Loading and Overview**
   - Checked data types, structure, and null values using `.info()` and `.isnull().sum()`

2. **Statistical Summary**
   - Descriptive statistics using `.describe()`  
   - Value counts and unique counts for categorical columns

3. **Univariate Analysis**
   - Visualized distribution of individual variables (e.g., Age, Fare, Pclass)
   - Used `histplot`, `countplot`, `boxplot` for visual insights

4. **Bivariate Analysis**
   - Explored relationships such as `Sex vs Survived`, `Pclass vs Survived` using bar plots and violin plots

5. **Multivariate Analysis**
   - Created pairplots to visualize multiple variable distributions
   - Generated a correlation heatmap to identify multicollinearity

6. **Handling Missing Data**
   - Identified missing values in 'Age', 'Cabin', and 'Embarked'
   - Suggested basic imputation techniques

7. **Observations & Insights**
   - Summarized patterns, anomalies, and correlations based on graphs and stats

---

## 📌 Key Insights:

- **Females had significantly higher survival rates** compared to males.
- **Passengers in 1st class** had a much better chance of survival than those in 3rd class.
- **Younger passengers and those who paid higher fares** were more likely to survive.
- Many null values were found in `Cabin`, suggesting missing data patterns worth exploring further.

---

## 📂 Files Included:

| File Name              | Description                                |
|------------------------|--------------------------------------------|
| `EDA_Titanic.ipynb`    | Jupyter Notebook with full analysis        |
| `EDA_Titanic.pdf`      | Exported PDF version of the notebook       |
| `README.md`            | Project description and documentation      |
| `train.csv` *(optional)* | Original dataset from Kaggle              |

---

## ✅ How to Run:

1. Clone this repository.
2. Install the dependencies:
   ```bash
   pip install pandas matplotlib seaborn
   ```
3. Open the Jupyter Notebook:
   ```bash
   jupyter notebook EDA_Titanic.ipynb
   ```
4. Explore the code, visuals, and insights step by step.

---

## 💬 Interview Preparation: Sample Questions Covered

- What is EDA and its importance?
- How do you visualize correlation?
- Difference between heatmap and pairplot?
- How to handle skewed data and multicollinearity?
- Explain univariate, bivariate, and multivariate analysis.

---

## 🙌 Acknowledgement:
This task was completed as part of the **Data Analyst Internship Program – Task 5 (EDA)**.  
Dataset © Kaggle – Titanic: Machine Learning from Disaster.

---

## 🔗 Submission Link:
[Submit Your Task Here](https://forms.gle/dF1EVUnqz2rQr2xu8)

---
