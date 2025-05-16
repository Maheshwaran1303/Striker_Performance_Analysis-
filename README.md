# ⚽ Striker Performance Analysis using Machine Learning

This project involves a comprehensive analysis of football strikers' performance using a dataset of striker metrics. It combines data cleaning, descriptive and statistical analysis, feature engineering, clustering, and predictive modeling to classify strikers as "Best Strikers" or "Regular Strikers".

---

## 📂 Dataset Overview

The dataset contains performance metrics for football strikers, including:
- Goals Scored
- Assists
- Shots on Target
- Dribbling Success
- Hold-up Play
- Aerial Duels Won
- Defensive Contribution
- Big Game Performance
- Consistency
- Conversion Rate
- Footedness, Nationality, Marital Status, etc.

---

## 🔧 Techniques Used

- **Data Cleaning & Imputation** (using `SimpleImputer`)
- **Data Type Conversion**
- **Descriptive Statistics**
- **Data Visualization** (`matplotlib`, `seaborn`)
- **Statistical Tests**
  - Shapiro-Wilk (normality)
  - Levene’s Test (homogeneity of variance)
  - ANOVA
  - Pearson Correlation
  - Linear Regression
- **Feature Engineering**
  - Total Contribution Score
  - Label Encoding & Dummy Variables
- **KMeans Clustering**
  - Elbow Method
  - Cluster Labeling
- **Logistic Regression Model**
  - Feature Scaling
  - Train-Test Split
  - Model Evaluation & Confusion Matrix

---

## 📊 Key Insights

| Metric | Result |
|--------|--------|
| Maximum Goals by a Striker | **34.26** |
| Right-Footed Players | **53.4%** |
| Best Goal Scoring Nationality | **Brazil** |
| Avg. Conversion Rate (Left-Footed) | **19.81%** |
| Left-Footed French Players | **42** |
| Hold-up Play & Consistency Correlation | **0.145** |
| Shapiro-Wilk p-value | **0.451** (Normal) |
| Levene’s Test p-value | **0.808** (Equal Variance) |
| Correlation Significance (p-value) | **0.0011** |
| Hold-up Play Regression Beta | **0.00148** |
| Avg. Total Contribution (Best Strikers) | **87.36** |
| Logistic Regression Accuracy | **92.5%** |
| Regular Strikers Predicted Correctly | **111** |
| Best Strikers Predicted Incorrectly | **3** |

---

## 📌 Project Structure

├── Strikers_performance.xlsx # Dataset
├── Striker_Performance_Analysis.ipynb # Jupyter Notebook
├── README.md # Project description


---

## 🎯 Conclusion

Through this project, we’ve built a complete pipeline from raw data to classification and prediction. The analysis helps:
- Identify top-performing strikers
- Compare performance across nationalities
- Predict striker types using machine learning

It serves as a valuable resource for **football analysts**, **coaches**, and **sports data scientists** to make data-driven decisions for team selection, talent identification, and strategy building.

---

## 💡 Future Enhancements

- Include more match-level data (pass accuracy, distance covered, etc.)
- Explore advanced ML models like Random Forest or SVM
- Deploy the model with a web-based dashboard

---

## 📬 Contact

Developed by **Maheshwaran**  
