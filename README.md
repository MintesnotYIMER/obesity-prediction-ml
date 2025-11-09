# 🧠 Estimation of Obesity Levels using Machine Learning
**Course:** MIAGE 2IS – Artificial Intelligence Project (University of Toulouse Capitole)  
**Year:** 2025  

---

## 👥 Team Members
- **Iana Miranda Caramé** – Data preprocessing, documentation  
- **Hritik Bikram Rawal** – Model evaluation, report writing  
- **Mintesnot Yimer** – Model development (SVM, Logistic Regression), optimization, data analysis  

---

## 📋 Project Overview
Obesity is a serious global public health issue. This project applies **machine learning** to predict obesity levels using **demographic, lifestyle, and behavioral data**.

The dataset contains **2,111 records with 17 attributes** (age, gender, diet, physical activity, etc.) collected from Mexico, Peru, and Colombia.  
The goal: classify individuals into **7 obesity categories**, from *Insufficient Weight* to *Obesity Type III*.

---

## 🧩 Tools & Libraries
- **Languages:** Python  
- **Libraries:** pandas, numpy, matplotlib, seaborn, scikit-learn  
- **Environment:** Google Colab  

---

## ⚙️ Methodology
1. **Data Cleaning and Exploration** – Verified no missing values; analyzed distributions with boxplots and histograms.  
2. **Feature Encoding** – Categorical to numerical; binary mapping and one-hot encoding applied.  
3. **Model Training** – Tested Decision Tree, Random Forest, Logistic Regression, and SVM (GridSearchCV for tuning).  
4. **Evaluation** – Accuracy, Precision, Recall, and Confusion Matrix.  

---

## 📈 Results Summary
| Model | Accuracy | Notes |
|--------|-----------|-------|
| Decision Tree | 94.3% | High interpretability |
| Random Forest | 95.5% | Slightly better accuracy |
| Logistic Regression | **96.7%** | Best balance of performance & interpretability |
| SVM | **96%** | Excellent generalization, low overfitting |

---

## 🧠 My Contributions (Mintesnot Yimer)
- Implemented **SVM and Logistic Regression** models in Python.  
- Performed **GridSearchCV optimization** for hyperparameters (C, kernel, gamma).  
- Analyzed **confusion matrices** and validated model generalization with learning curves.  
- Helped finalize the **report** and interpret health-related results.

---

## 📊 Key Insights
- Obesity strongly correlated with caloric intake and low physical activity.  
- SVM and Logistic Regression achieved high accuracy with minimal overfitting.  
- Logistic Regression provides better interpretability for health policy use.

---

## 💻 How to Run
1. Open the notebook → [Google Colab Link](https://colab.research.google.com/drive/17Kr0sl3KtIXKjX-J-10tJfk4P6hMUq9R?usp=sharing)  
2. The dataset is hosted in this repository.  
Colab loads it automatically from:  
[Raw CSV Link](https://raw.githubusercontent.com/MintesnotYIMER/obesity-prediction-ml/refs/heads/main/ObesityDataSet_raw_and_data_sinthetic.csv)

3. Run all cells; view accuracy metrics and graphs.

---

## 📂 Files
- `obesity_classification.ipynb` → Main Colab notebook  
- `AI_Obesity_Report.pdf` → Full project report  

---

## 🏁 Conclusion
This project demonstrates how **machine learning** can assist in **early obesity risk detection** using structured health data.  
It highlights the power of combining **data-driven insights** with **public health strategies**.

📘 [Full Report (PDF)](https://github.com/MintesnotYIMER/obesity-prediction-ml/blob/main/Report_Obesity_Prediction.pdf)  
💻 [Google Colab](https://colab.research.google.com/drive/17Kr0sl3KtIXKjX-J-10tJfk4P6hMUq9R?usp=sharing)
