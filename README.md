# Titanic-Project
Titanic data analysis and prediction project 

---

# 🚢 Titanic Survival Analysis & Prediction

## 📌 Overview

This project analyzes the Titanic passenger dataset to identify key factors influencing survival and build a predictive model using a **Random Forest Classifier**. It includes **data exploration, visualization, feature engineering, and machine learning** to answer the given set of 20 tasks.

---

## 📋 Project Tasks

### **Data Exploration & Visualization**

1. **Survival Count** – How many passengers survived and how many didn’t? Plot a bar chart.
2. **Gender Survival Percentage** – Compare percentage of males vs females who survived (countplot or pie chart).
3. **Class Survival Rate** – Compare survival rate across passenger classes (Pclass). Identify the highest survival rate.
4. **Age Analysis** – Plot age distribution, compare average age of survivors vs non-survivors.
5. **Family Effect** – Do passengers with family (SibSp or Parch) have higher survival rates?
6. **Fare Analysis** – Survival rate for passengers who paid more than the average fare.
7. **Age Groups** – Create “child” (<16), “adult” (16–60), “senior” (>60) groups; find which group survived most.
8. **Missing Values** – Check for missing values and document handling before modeling.
9. **Correlation Heatmap** – Create a heatmap for numerical columns and interpret.
10. **Embarked Survival** – Plot survival counts for each Embarked location; find which had the highest survival rate.

---

### **Modeling with Random Forest**

11. Train a Random Forest classifier and print the accuracy.
12. Change `n_estimators` (10, 100, 500) and observe accuracy changes.
13. Use `.predict()` for the first 10 rows and compare with actual survival values.
14. Plot a confusion matrix for the Random Forest model and interpret results.
15. List the top 3 most important features according to the Random Forest model.
16. Use `cross_val_score` to evaluate model performance; report average accuracy.
17. Change `max_depth` of the Random Forest and note effects on accuracy & overfitting.
18. Compare Random Forest accuracy with a Decision Tree; explain which is better and why.

---

### **Critical Thinking & Interpretation**

19. Identify 3 factors that most affect survival based on analysis and model.
20. Suggest extra features to collect that could improve model performance.

---

## 🛠 Technologies Used

* **Python**
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

---

## 🚀 Installation & Usage

1. Clone this repository:

```bash
git clone https://github.com/yourusername/titanic-project.git
cd titanic-project
```

2. Install dependencies:

```bash
pip install -r requirements.txt
```

3. Run the analysis:

```bash
python titanic_analysis.py
```

---

## 📂 Project Structure

```
📁 titanic-project/
 ├── README.md                 # Titanic dataset
 ├── Titanic-Dataset.csv       # Main Python script
 └── Titanic_Project.ipynb     # Project documentation
```


## 🚀 Installation & Usage

1. **Clone the repository**

```bash
git clone https://github.com/yourusername/titanic-project.git
cd titanic-project
```

2. **Install dependencies**

```bash
pip install -r requirements.txt
```

3. **Run the analysis**

```bash
python titanic_analysis.py
```

---
## 📈 Example Insights

* **Highest survival rate:** First-class female passengers.
* **Top 3 survival factors:** Passenger Class, Sex, Fare.
* **Random Forest Accuracy:** \~80% (varies with parameters).




