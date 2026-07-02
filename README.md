# 🧠 COVID-19 Impact on Student Mental Health using Machine Learning

<p align="center">

![Python](https://img.shields.io/badge/Python-3.10+-blue?style=for-the-badge&logo=python)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-ML-orange?style=for-the-badge&logo=scikitlearn)
![SHAP](https://img.shields.io/badge/Explainable%20AI-SHAP-red?style=for-the-badge)
![LIME](https://img.shields.io/badge/XAI-LIME-green?style=for-the-badge)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?style=for-the-badge&logo=jupyter)
![License](https://img.shields.io/badge/License-MIT-blue?style=for-the-badge)

</p>

---

# 📖 Overview

The **COVID-19 pandemic** has had a profound impact on students' mental health, disrupting academic routines, social interactions, and overall well-being. This project leverages **Machine Learning** and **Explainable Artificial Intelligence (XAI)** to analyze psychological factors affecting students and predict mental health outcomes based on behavioral, academic, and lifestyle features.

Unlike traditional prediction models, this project emphasizes **model transparency** by integrating **SHAP** and **LIME**, allowing users to understand **why** a prediction was made rather than simply obtaining the prediction.

---

# 🎯 Objectives

✅ Analyze the impact of COVID-19 on students' mental health.

✅ Perform comprehensive Exploratory Data Analysis (EDA).

✅ Identify significant factors influencing mental health.

✅ Train and compare multiple Machine Learning models.

✅ Explain model predictions using SHAP and LIME.

✅ Visualize insights through statistical plots.

---

# ✨ Key Features

- 📊 Comprehensive Exploratory Data Analysis (EDA)
- 🧹 Data Cleaning & Preprocessing
- 📈 Multiple Statistical Visualizations
- 🤖 Machine Learning Classification
- 🔍 Explainable AI using SHAP
- 💡 Local Prediction Explanation using LIME
- 📉 Model Performance Comparison
- 🎯 Feature Importance Analysis
- 📑 Detailed Performance Metrics

---

# 📂 Dataset

The dataset contains information collected from students during the COVID-19 pandemic.

## 📌 Features

- 👤 Age
- 🚻 Gender
- 🎓 Academic Level
- 📚 Study Hours
- 😴 Sleep Duration
- 🏃 Physical Activity
- 📱 Screen Time
- 👨‍👩‍👧 Family Support
- 🤝 Social Interaction
- 💰 Financial Stress
- 😟 Anxiety Level
- 😔 Depression Indicators
- 😫 Stress Level
- 🌐 Internet Usage
- 📖 Academic Performance
- ❤️ Lifestyle Factors

### 🎯 Target Variable

**Mental Health Status**

---

# 📊 Exploratory Data Analysis (EDA)

Several visualization techniques were used to gain insights into the dataset.

---

## 🥧 Pie Charts

Used for:

- Gender Distribution
- Mental Health Distribution
- Academic Level Distribution

### Purpose

- Class balance analysis
- Percentage distribution
- Category comparison

---

## 📊 Bar Charts

Visualized:

- Stress Level
- Anxiety Level
- Depression Categories
- Academic Performance
- Sleep Quality

### Purpose

- Frequency comparison
- Category analysis
- Distribution understanding

---

## 📈 Scatter Plots

Relationships analyzed:

- Sleep Hours vs Stress
- Study Hours vs Mental Health
- Screen Time vs Anxiety
- Physical Activity vs Depression

### Purpose

- Trend detection
- Correlation analysis
- Cluster identification

---

## 📦 Box Plots

Used for:

- Outlier Detection
- Distribution Analysis

Variables:

- Sleep Hours
- Screen Time
- Study Hours
- Stress Level

---

## 🌡️ Heatmap

Correlation Heatmap generated using Pearson Correlation.

### Purpose

- Correlation Analysis
- Feature Relationships
- Multicollinearity Detection

---

## 📉 Histograms

Used for:

- Age
- Sleep Duration
- Study Hours
- Screen Time

### Purpose

- Data Distribution
- Skewness Analysis
- Frequency Visualization

---

## 📌 Correlation Analysis

The heatmap helped identify highly correlated variables affecting students' mental health and guided feature selection for machine learning models.

---

# 🧹 Data Preprocessing

The dataset underwent extensive preprocessing before training.

### ✔ Steps Performed

- ✅ Missing Value Handling
- ✅ Duplicate Removal
- ✅ Label Encoding
- ✅ One-Hot Encoding
- ✅ Feature Scaling
- ✅ Feature Selection
- ✅ Data Normalization
- ✅ Train-Test Split
- ✅ Data Validation

---

# 🤖 Machine Learning Models

The following algorithms were trained and evaluated.

| Model | Purpose |
|--------|----------|
| 📈 Logistic Regression | Baseline Classification |
| 🌳 Decision Tree | Rule-Based Learning |
| 🌲 Random Forest | Ensemble Learning |
| ⚡ Support Vector Machine | Margin-Based Classification |
| 👥 K-Nearest Neighbors | Distance-Based Learning |
| 📊 Naive Bayes | Probabilistic Classification |
| 🚀 Gradient Boosting | Boosting Algorithm |
| 🔥 XGBoost *(Optional)* | Advanced Boosting |
| 🧠 Multi-Layer Perceptron | Neural Network |

---

# 📏 Model Evaluation Metrics

The models were evaluated using:

- 🎯 Accuracy
- 📌 Precision
- 🔄 Recall
- ⚖️ F1 Score
- 📈 ROC-AUC Score
- 📊 Confusion Matrix
- 📑 Classification Report

---

# 🔍 Explainable AI (XAI)

Machine learning predictions become significantly more trustworthy when users understand how they are made.

This project integrates **Explainable AI (XAI)** techniques to improve transparency.

---

# 🟥 SHAP (SHapley Additive Explanations)

SHAP explains the contribution of every feature toward the final prediction.

### SHAP Visualizations

- 📊 SHAP Summary Plot
- 📈 SHAP Bar Plot
- 💥 SHAP Force Plot
- 🌊 SHAP Waterfall Plot
- 📉 SHAP Dependence Plot

### Benefits

- 🌍 Global Feature Importance
- 🎯 Local Prediction Explanation
- 🤖 Model Transparency
- 📊 Feature Interaction Analysis

---

# 🟩 LIME (Local Interpretable Model-Agnostic Explanations)

LIME explains individual predictions using an interpretable local model.

### LIME Outputs

- 📑 Prediction Explanation
- 📈 Feature Contribution
- 💡 Local Feature Importance

### Benefits

- Easy Interpretation
- Model Independent
- Trustworthy Predictions
- Human Readable Explanations

---

# 📌 Feature Importance

Important features identified include:

- 😫 Stress Level
- 😟 Anxiety
- 😔 Depression
- 😴 Sleep Duration
- 📱 Screen Time
- 🏃 Physical Activity
- 👨‍👩‍👧 Family Support
- 🤝 Social Interaction
- 📚 Academic Pressure

Feature importance was validated using:

- ✅ SHAP
- ✅ LIME
- ✅ Random Forest Feature Importance

---

# 🛠️ Tech Stack

## 👨‍💻 Programming

- 🐍 Python

## 📚 Libraries

- Pandas
- NumPy
- Scikit-Learn
- Matplotlib
- Seaborn
- SHAP
- LIME
- Joblib

## 💻 IDE

- Jupyter Notebook
- Google Colab
- VS Code

---

# 📁 Project Structure

```text
COVID19-Student-Mental-Health/
│
├── dataset/
│   └── covid_student_mental_health.csv
│
├── notebooks/
│   └── Mental_Health_Analysis.ipynb
│
├── models/
│   └── trained_model.pkl
│
├── images/
│   ├── pie_chart.png
│   ├── bar_chart.png
│   ├── scatter_plot.png
│   ├── box_plot.png
│   ├── heatmap.png
│   ├── histogram.png
│   ├── shap_summary.png
│   ├── shap_bar.png
│   ├── shap_force.png
│   ├── lime_prediction.png
│   ├── roc_curve.png
│   └── confusion_matrix.png
│
├── README.md
├── requirements.txt
└── LICENSE
```

---

# 🚀 Installation

```bash
git clone https://github.com/yourusername/COVID19-Student-Mental-Health.git

cd COVID19-Student-Mental-Health

pip install -r requirements.txt

jupyter notebook
```

---

# 📦 Requirements

```text
Python >= 3.10

numpy
pandas
matplotlib
seaborn
scikit-learn
shap
lime
joblib
jupyter
xgboost
```

---

# 📊 Results

✔ Successfully analyzed the impact of COVID-19 on student mental health.

✔ Performed extensive Exploratory Data Analysis.

✔ Compared multiple Machine Learning algorithms.

✔ Evaluated model performance using various metrics.

✔ Explained predictions using SHAP and LIME.

✔ Identified key factors influencing mental health.

✔ Improved model interpretability and transparency.

---

# 🚀 Future Enhancements

- 🌐 Deploy using Streamlit
- 📱 Build a Web Dashboard
- ☁️ Cloud Deployment
- 📊 Real-Time Prediction
- 🧠 Deep Learning Models
- 🤖 AI-Based Mental Health Chatbot
- 📈 Interactive Dashboard
- 📂 Larger Public Dataset Integration

---

# 🤝 Contributing

Contributions are welcome!

If you have suggestions or improvements, feel free to:

⭐ Star the repository

🍴 Fork the project

🐛 Open an Issue

📩 Submit a Pull Request

---

# 👨‍💻 Author

## **Hitesh Kumar S**

🎓 B.Tech Computer Science and Engineering

🏫 Amrita Vishwa Vidyapeetham, Bengaluru

💻 Passionate about Machine Learning, AI, Data Science, and Explainable AI.

---

# 🙏 Acknowledgements

- ❤️ Open Source Community
- 🐍 Python Developers
- 📚 Scikit-Learn
- 📊 Pandas
- 📈 Matplotlib
- 🎨 Seaborn
- 🔍 SHAP
- 💡 LIME
- 🎓 Researchers working on Mental Health

---

<div align="center">

### ⭐ If you found this project useful, don't forget to star the repository! ⭐

**Made with ❤️ using Python, Machine Learning, SHAP & LIME**

</div>
