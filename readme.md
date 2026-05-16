# 🧠 Student Depression Prediction using Data Mining

Predicting student depression risk based on academic, social, and lifestyle factors using Machine Learning and Data Mining approaches.

---

## 📌 Project Overview

Mental health issues among university students have become an increasingly important concern, especially depression caused by academic pressure, financial stress, unhealthy lifestyles, and social challenges.

This project aims to analyze and predict student depression risk using:

- **Naïve Bayes Classifier** for prediction/classification
- **K-Means Clustering** for student segmentation
- **PCA (Principal Component Analysis)** for dimensionality reduction
- **Interactive Dashboard Visualization** for insight presentation

Developed as part of a Data Mining course project at Telkom University.

---

## 🎯 Objectives

- Predict whether a student is at risk of depression
- Identify hidden behavioral patterns through clustering
- Analyze academic and social factors influencing depression
- Support early detection strategies using data-driven approaches

---

## 📂 Dataset Information

- **Source:** Kaggle
- **Dataset:** Student Depression Dataset
- **Total Records:** 27,901 students
- **Features:** 13 variables

### Features Included

| Category | Features |
|---|---|
| Academic | Academic Pressure, CGPA, Study Satisfaction |
| Lifestyle | Sleep Duration, Dietary Habits, Work/Study Hours |
| Psychological | Suicidal Thoughts, Family Mental Illness History |
| Financial | Financial Stress |
| Demographic | Age, Gender, Degree |

---

## ⚙️ Technologies Used

| Technology | Purpose |
|---|---|
| Python | Data processing & modeling |
| Pandas | Data manipulation |
| NumPy | Numerical computation |
| Scikit-learn | Machine learning |
| Matplotlib / Seaborn | Visualization |
| Streamlit | Dashboard development |
| Google Colab | Development environment |

---

## 🔄 Project Workflow

```text
Data Collection
      ↓
Data Understanding
      ↓
Data Cleaning & Preprocessing
      ↓
Feature Encoding & Scaling
      ↓
Train-Test Split
      ↓
Naïve Bayes Classification
      ↓
K-Means Clustering
      ↓
Evaluation & Visualization
      ↓
Interactive Dashboard
```

---

## 🧹 Data Preprocessing

The preprocessing stage included:

- Handling missing values
- Duplicate checking
- Outlier detection using IQR
- One-Hot Encoding for categorical variables
- Feature Scaling using Min-Max Scaling

### Preprocessing Results

| Process | Result |
|---|---|
| Missing Values | 0 |
| Duplicate Data | 0 |
| Records Before Cleaning | 27,901 |
| Records After Cleaning | 27,880 |

---

## 🤖 Machine Learning Models

### 1️⃣ Naïve Bayes Classification

Used to classify whether a student is:

- **0 → Not Depressed**
- **1 → Depressed**

#### Model Performance

| Metric | Score |
|---|---|
| Accuracy | 88% |
| Precision (Depression) | 83% |
| Recall (Depression) | 85% |
| F1-Score (Depression) | 84% |

#### Confusion Matrix

| | Predicted Positive | Predicted Negative |
|---|---|---|
| Actual Positive | 2733 | 499 |
| Actual Negative | 569 | 1779 |

---

### 2️⃣ K-Means Clustering

K-Means clustering was applied to group students based on similar psychological and academic characteristics.

#### Optimal Cluster Selection

- Elbow Method
- Silhouette Score
- Final chosen cluster: **K = 5**

#### Cluster Interpretation

| Cluster | Description |
|---|---|
| Cluster 0 | Highly Vulnerable Students |
| Cluster 1 | Relatively Stable Students |
| Cluster 2 | Small Stable Group |
| Cluster 3 | Vulnerable Students |
| Cluster 4 | Students Requiring Special Attention |

---

## 📊 Key Insights

Important factors influencing depression risk include:

- Academic Pressure
- Sleep Duration
- Financial Stress
- Suicidal Thoughts
- Study Satisfaction

Students with:
- high academic pressure,
- short sleep duration,
- high financial stress,
- and suicidal thoughts

tended to have significantly higher depression risk.

---

## 📈 PCA Visualization

Principal Component Analysis (PCA) was used to:

- Reduce high-dimensional data
- Improve clustering efficiency
- Visualize student segmentation in 2D space

---

## 🖥️ Dashboard

The interactive dashboard provides visualization for:

- Depression distribution
- Cluster segmentation
- Mental health indicators
- Academic pressure trends
- Prediction insights

---

## 🚀 Future Improvements

Potential future enhancements:

- Implement Random Forest or SVM
- Real-time mental health monitoring
- Integration with university systems
- Enhanced dashboard interactivity
- Localized institutional datasets

---

## 👥 Contributors

| Name | Role |
|---|---|
| Anisa Hanun | Data Analysis & Modeling |
| Sridamai Wati Panjaitan | Research & Documentation |
| Alya Davina Maharani | Data Processing |
| Haipa Zuhaira | Visualization & Dashboard |

---

# LINK GCOLAB: https://colab.research.google.com/drive/1RLCUrSK_6QnDFKq5cBaIdvoD4SuJqRoL?usp=sharing
# LINK LAPORAN: https://drive.google.com/file/d/1ah4UJtYBZl0kDDPrin6InRvQsg8wIaa3/view?usp=sharing
