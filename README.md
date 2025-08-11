# 🛳 Titanic Dataset – Exploratory Data Analysis (EDA)

## 📌 Objective
This project is part of **Task 5** of the Data Analyst Internship program.  
The aim is to perform **Exploratory Data Analysis (EDA)** on the Titanic dataset to identify patterns, trends, and anomalies that influence passenger survival.

---

## 📂 Dataset
- **Source:** [Kaggle – Titanic: Machine Learning from Disaster](https://www.kaggle.com/c/titanic/data?select=train.csv)
- **File Used:** `train.csv`
- **Description:** The dataset contains passenger details such as age, gender, ticket fare, passenger class, and survival status.

---

## 🛠 Tools & Libraries
- **Python**
- **Pandas** – Data manipulation
- **Matplotlib & Seaborn** – Data visualization
- **Google Colab** – Notebook environment

---

## 📊 Steps Performed
1. **Data Loading & Inspection**
   - Used `.info()`, `.describe()`, `.value_counts()` to understand the dataset.
2. **Data Cleaning**
   - Checked for missing values.
3. **Univariate Analysis**
   - Plotted histograms, boxplots, and bar charts for individual features.
4. **Bivariate Analysis**
   - Explored relationships between variables using countplots, scatterplots, and correlation heatmaps.
5. **Multivariate Analysis**
   - Used `sns.pairplot()` to identify trends across multiple features.
6. **Observations & Insights**
   - Wrote detailed observations for each visual.
7. **Summary of Findings**
   - Provided key conclusions from the analysis.

---

## 📈 Visualizations
The notebook includes:
- Histograms (Age, Fare)
- Boxplots (Fare)
- Bar charts (Gender count, Passenger class count)
- Countplots (Survival by gender and class)
- Scatterplots (Age vs Fare)
- Heatmap (Correlation matrix)
- Pairplot (Age, Fare, Pclass, Survived)

---

## 📌 Key Insights
- Women had a higher survival rate than men.
- First-class passengers had better survival chances compared to other classes.
- Younger passengers had slightly better chances of survival.
- Higher ticket fares generally correlated with higher survival probability.

---

## 📄 Deliverables
- **Jupyter Notebook:** `Titanic_EDA_Task5.ipynb`
- **PDF Report:** `Titanic_EDA_Task5_Report.pdf`
- **Dataset:** `train.csv` 

---

