# 🌟 Elevvo Machine Learning Internship Portfolio

This repository contains all of my completed projects and bonus assignments created as part of my 2-week internship at **Elevvo Pathways** in the **Machine Learning Track**. Each task is designed to tackle a different core competency in data science, ranging from regression and clustering to advanced multi-class classification.

---

## 📁 Table of Contents

- [Task 1: Student Score Prediction](#task-1-student-score-prediction)
- [Task 2: Customer Segmentation](#task-2-customer-segmentation)
- [Task 3: Forest Cover Type Classification](#task-3-forest-cover-type-classification)
- [Acknowledgements](#acknowledgements)

---

## 🎓 Task 1: Student Score Prediction

### 📌 Objective
To predict student exam scores using regression models based on performance factors such as study hours, sleep duration, and attendance.

### 🧠 Models & Techniques
- **Linear Regression**: Baseline model to establish initial performance.
- **Polynomial Regression (degree 2)**: Captures non-linear relationships between features and scores.

### 📊 Evaluation Metrics
- **Mean Squared Error (MSE)**: Measures average squared difference between predicted and actual scores.
- **R² Score**: Indicates how well features explain the variance in scores.

### 📈 Key Insights
- Polynomial Regression outperformed the linear baseline.
- Feature engineering and interaction terms significantly improved model accuracy.

---

## 🛍️ Task 2: Customer Segmentation

### 📌 Objective
To identify distinct customer groups within a mall's clientele based on annual income and spending habits.

### 🧠 Models & Techniques
- **K-Means Clustering**: Primary algorithm for segmentation.
- **Elbow Method**: Used to determine optimal number of clusters.
- **Feature Scaling**: StandardScaler applied to normalize features.

### 📊 Key Insights
- Identified five distinct customer segments, including:
  - *High Income, Low Spending* (Careful Spenders)
  - *Low Income, High Spending* (Target for Promotions)
- Cluster visualization revealed actionable personas for marketing.

---

## 🌲 Task 3: Forest Cover Type Classification

### 📌 Objective
To classify the forest cover type (7 classes) for a 30x30 meter land patch using cartographic and environmental data.

### 🧠 Models & Techniques
- **Random Forest**: Strong ensemble baseline model.
- **XGBoost**: High-performance gradient boosting model.
- **Hyperparameter Tuning**: GridSearchCV used to optimize XGBoost parameters.

### 📊 Evaluation Metrics
- **Classification Report**: Precision, Recall, F1-Score for each forest type.
- **Confusion Matrix**: Diagnosed model performance across classes.
- **Feature Importance**: Identified key predictors of forest type.

### 📈 Key Insights
- Tuned XGBoost achieved ~96% accuracy on the test set.
- Confusion mostly occurred between the two most common forest types, suggesting room for improvement.

---


---

## 🙏 Acknowledgements

I would like to thank **Elevvo Pathways** for providing this invaluable internship experience. The hands-on projects were instrumental in solidifying my machine learning knowledge and practical data science skills.

