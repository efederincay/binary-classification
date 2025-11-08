#  Binary Classification: Heart Disease Prediction

##  Project Overview
This project predicts the presence of **heart disease** using patient health data.  
It compares three machine learning models:
- **Logistic Regression**
- **Neural Network (Keras Sequential Model)**
- **Random Forest**

The analysis covers data cleaning, model training, evaluation, and ROC-AUC comparison.

---

## 📊 Dataset
The dataset used is the **UCI Heart Disease Dataset**, which contains features such as:
- Age, sex, chest pain type, cholesterol, resting blood pressure  
- Exercise-induced angina, maximum heart rate, and other health indicators  

**Target variable:**  
`1` → Heart disease present  
`0` → No heart disease  

Dataset source:  
🔗 [UCI Heart Disease Dataset](https://archive.ics.uci.edu/ml/datasets/heart+disease)

---

## ⚙️ Steps
1. **Exploratory Data Analysis (EDA)**  
   - Distribution plots, correlation matrix, and class balance  

2. **Data Preprocessing**  
   - Missing values handled  
   - Feature scaling with `StandardScaler`  
   - Train-test split (80–20)

3. **Model Training**  
   - Logistic Regression  
   - Neural Network (Dense layers with ReLU & Sigmoid)  
   - Random Forest Classifier  

4. **Evaluation Metrics**  
   - Accuracy, Precision, Recall, F1-Score  
   - Confusion Matrix Visualization  
   - ROC-AUC Curves for all models  

---

## 🧠 Results Summary

| Model | Accuracy | Precision | Recall | F1 Score | ROC-AUC |
|--------|-----------|------------|---------|-----------|----------|
| Logistic Regression | 0.885 | 0.882 | 0.909 | 0.896 | 0.93 |
| Neural Network | 0.918 | 0.938 | 0.909 | 0.923 | 0.95 |
| Random Forest | 0.869 | 0.879 | 0.879 | 0.879 | 0.90 |

✅ The **Neural Network** achieved the highest ROC-AUC and F1 score, showing the most consistent performance.  
Random Forest showed slight overfitting but still performed well overall.

---

## 🚀 Future Improvements
- Apply **hyperparameter tuning** for each model  
- Use **k-fold cross-validation** to increase reliability  
- Add **feature engineering** and **outlier handling**  
- Implement **SHAP** or **LIME** for model explainability  

---

## 📁 File
- `Binary_Classification_Assignment.ipynb` → full code and visualizations

---

## 🧾 Author
**Efe Eşref Derinçay**  
Master’s in Data Science – University of Europe for Applied Sciences, Berlin  
 Project completed using Python, Pandas, Scikit-learn, Matplotlib, and Keras.
