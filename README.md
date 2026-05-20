# Student Depression Detection using Machine Learning

## 📌 Project Overview
Mental health issues among students are increasing rapidly due to academic pressure, financial stress, unhealthy lifestyles, and social challenges. This project focuses on predicting student depression using Machine Learning classification models.

The system analyzes demographic, academic, and lifestyle-related factors to identify students who may be at risk of depression, enabling early intervention and proactive mental health support.

---

## 🎯 Objective
The main objective of this project is to build and evaluate Machine Learning models capable of predicting depression among students using supervised learning techniques.

---

## 🛠️ Technologies Used

### Programming Language
- Python

### Libraries & Tools
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- Pickle

---

## 📂 Dataset
Dataset Source:
- Kaggle Student Depression Dataset

Dataset includes features such as:
- Gender
- Age
- Academic Pressure
- Work Pressure
- CGPA
- Sleep Duration
- Dietary Habits
- Financial Stress
- Work/Study Hours
- Family History of Mental Illness

Target Variable:
- Depression (0 = No, 1 = Yes)

---

## ⚙️ Project Workflow

### 1. Data Preprocessing
- Handling missing values
- Removing inconsistent data
- Label Encoding categorical variables
- Data quality verification

### 2. Exploratory Data Analysis (EDA)
Performed multiple visual analyses including:
- Depression Distribution
- Gender Distribution
- Academic Pressure vs Depression
- Sleep Duration Analysis
- Correlation Heatmap
- Confusion Matrix Analysis

### 3. Machine Learning Models
Implemented and compared:
- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier

---

## 📊 Model Performance

### 🏆 Best Performing Model
Random Forest Classifier

### Results
- Accuracy: **83.6%**
- Recall: **88.1%**
- Precision: **84.2%**

### Confusion Matrix Results
- True Positives (TP): 1061
- True Negatives (TN): 689
- False Positives (FP): 199
- False Negatives (FN): 143

---

## 🔍 Key Findings
The analysis identified the following major contributors to student depression:
- High Academic Pressure
- Sleep Deprivation
- Financial Stress
- Excessive Work/Study Hours

The study revealed that students sleeping less than 5 hours per night showed significantly higher depression risk.

---

## 📈 Feature Importance
The Random Forest model identified the following as the most influential features:
1. Academic Pressure
2. Sleep Duration
3. Financial Stress
4. Work/Study Hours

---

## 🚀 Future Scope
Future improvements for this project include:
- Hyperparameter Optimization
- Grid Search & Random Search
- Deep Learning Models (MLPs)
- Explainable AI (SHAP/LIME)
- Real-time Web Application Deployment
- NLP-based Sentiment Analysis

---

## 💡 Applications
- Early student mental health detection
- Educational counseling systems
- Healthcare analytics
- Predictive mental health monitoring

---

## 📁 Project Structure

```bash
student-depression-detection/
│
├── dataset.csv
├── student_depression.ipynb
├── model.pkl
├── requirements.txt
├── README.md
└── Python Report CA2.pdf
```

---

## 👨‍💻 Author
**Mannuru Mahesh**  
M.Tech Data Science & Analytics  
Lovely Professional University

---

## 🙏 Acknowledgement
Special thanks to **Dr. Karan Bajaj** for continuous guidance and support throughout the project.

---

## 📌 Conclusion
This project demonstrates how Machine Learning can effectively support mental health prediction systems by identifying at-risk students using academic, demographic, and lifestyle indicators.

The Random Forest Classifier achieved the best performance and proved highly effective in predicting student depression with strong accuracy and recall.
