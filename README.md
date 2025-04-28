# Titanic - Exploratory Data Analysis (EDA)

Welcome to the **Titanic EDA Project**! This project focuses on extracting insights from the Titanic dataset using Python libraries like **Pandas**, **Seaborn**, and **Matplotlib**.

---

## 📚 Project Objective
- Perform detailed exploratory data analysis (EDA) on the Titanic dataset.
- Identify important features influencing survival.
- Extract statistical and visual insights.
- Prepare the dataset for future modeling.

---

## 🛠 Tools Used
- Python
- Pandas
- Matplotlib
- Seaborn
- NumPy

---

## 📋 Steps Followed

### 1. Data Overview
- Checked dataset shape, data types, and missing values.
- Performed basic statistical descriptions using `.describe()` and `.info()`.

### 2. Univariate Analysis
- Used **countplots** for categorical features (`Sex`, `Pclass`, `Embarked`, `Survived`).
- Used **histograms** and **KDE plots** for numerical features (`Age`, `Fare`, `SibSp`, `Parch`).

### 3. Bivariate Analysis
- Barplots to explore survival relationships with `Sex`, `Pclass`, `Embarked`.
- KDE plots and Boxplots for `Age` and `Fare` vs `Survival`.

### 4. Multivariate Analysis
- Created a **pairplot** to explore relationships between multiple variables.
- Generated a **sunburst chart** to visualize hierarchical survival rates.

### 5. Outlier Detection
- Used **boxplots** to detect outliers in `Age` and `Fare`.

### 6. Feature Engineering
- Binned `Fare` and `Age` into categories.
- Created new features `FareBin` and `AgeBin`.

### 7. Correlation Analysis
- Plotted a **correlation heatmap** to visualize relationships among numerical features.

### 8. Observations and Insights
- Provided a 1-line observation for each visual.
- Summarized key findings and insights.

---

## 🖍️ Why Perform Univariate Analysis Before Solving Missing Values?

> **We perform univariate analysis before solving missing values because it helps us understand the original distribution of data, the extent and nature of missingness, and ensures that any filling or dropping of data is done based on informed decisions, preserving the true patterns in the dataset.**

---

## 📊 Key Insights
- Females had a significantly higher survival rate compared to males.
- 1st class passengers had the highest survival rates.
- Children (0-12 years) had better chances of survival than adults and seniors.
- Higher fare-paying passengers had better survival chances.
- Embarkation from Cherbourg (C) slightly improved survival probability.

---

## 📄 Deliverables
- **Jupyter Notebook** with all EDA code, visuals, and observations.
- **PDF Report** summarizing key findings and insights.

---

## 🖥️ How to Download and Run the Code

1. **Clone the Repository:**
```bash
git clone <repository_link>
```

2. **Navigate into the Project Directory:**
```bash
cd titanic-eda-project
```

3. **Install Required Libraries:**
```bash
pip install pandas matplotlib seaborn numpy plotly
```

4. **Download the Titanic Dataset:**
- You can download the dataset from [Kaggle Titanic Competition](https://www.kaggle.com/c/titanic/data).
- Place `train.csv` and `test.csv` inside the project directory.

5. **Run the Jupyter Notebook:**
```bash
jupyter notebook Titanic_EDA_Final.ipynb
```

6. **View the PDF Report:**
- The generated PDF (`Titanic_EDA_Final_Report.pdf`) is available inside the project folder.

---

## 📢 Notes
- No modeling or predictions were done in this phase.
- The test dataset was cleaned separately for future prediction steps.

---

Happy Analyzing! 🚀
