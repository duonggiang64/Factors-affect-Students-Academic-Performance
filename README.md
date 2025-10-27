 ### Factors Affecting Students’ Academic Performance ###

---

### 🎓 Project Summary

This project explores how demographic and socioeconomic factors influence students’ academic performance using R. The analysis is based on exam score data (math, reading, and writing) along with attributes such as gender, parental education, lunch type, and test preparation status.

### 🧠 Objectives

* Identify key variables that affect student achievement.
* Visualize performance differences across demographic groups.
* Build predictive and explanatory models to assess factor importance.

### 🗂️ Data & Preparation

The dataset includes 100 student records with variables for **Gender**, **Parental Education**, **Lunch**, **Test Preparation**, and exam scores. Data cleaning and transformation steps recoded categorical variables into numeric form for analysis.

### ⚙️ Methods

* **Descriptive Statistics:** Summary tables of exam scores using `stargazer`.
* **Visualization:** Bar plots comparing scores by gender, parental education, lunch type, and test preparation using `ggplot2`.
* **Correlation Analysis:** Relationship matrix and heatmap to explore variable associations.
* **Regression Modeling:** Linear regression models to estimate the effects of lunch type, parental education, and test preparation on math, reading, and writing scores.
* **Machine Learning:** Random Forest classifier to predict overall performance (“Good” or “Bad”) and evaluate variable importance.

### 📊 Key Findings

* Students with **standard lunch** and those who **completed test preparation** scored higher across all subjects.
* **Parental education** showed a positive relationship with academic performance.
* **Lunch type** and **test preparation** were the most influential variables in the Random Forest model.

### 🧾 Tools & Libraries

R (tidyverse, ggplot2, stargazer, corrplot, randomForest, equatiomatic)

---

