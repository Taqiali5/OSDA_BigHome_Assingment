# 🚀 Machine Learning Classification on Real-World Datasets  
### 👤 Syed Taqi Ali  

---

## 📌 Project Overview  
This project applies **machine learning classification techniques** to solve real-world problems in **healthcare and HR analytics**.  

Three datasets are analyzed:
- ❤️ Heart Disease Prediction  
- 🎗️ Breast Cancer Classification  
- 👨‍💼 Employee Attrition Prediction  

The goal is to **build efficient predictive models**, compare performance, and optimize results using **parameter tuning and cross-validation**.

---

## 🎯 Business Problem  

- **Healthcare (Heart & Cancer):**  
  Predict diseases early to support better medical decisions  

- **HR Analytics (Employee):**  
  Predict whether an employee will leave the company  

---

## 📂 Datasets  

### ❤️ Heart Disease Dataset  
- Features:  
  `Age, Sex, cp, trestbps, chol, fbs, restecg, thalach, exang, oldpeak, slope, ca, thal`  
- Target: Disease presence  

🔗 https://www.kaggle.com/datasets/arezaei81/heartcsv  

---

### 🎗️ Breast Cancer Dataset  
- 500 instances (Malignant & Benign)  
- Key Features:
  - Mean Radius  
  - Mean Texture  
  - Mean Perimeter  
  - Mean Area  
  - Mean Smoothness  

🔗 https://archive.ics.uci.edu/dataset/17/breast+cancer+wisconsin+diagnostic  

---

### 👨‍💼 Employee Dataset  
- Features:
  - Education, Joining Year, City  
  - Payment Tier, Age, Gender  
  - Ever Benched, Experience  

- 🎯 Target: **Leave or Not**  

🔗 https://www.kaggle.com/datasets/tawfikelmetwally/employee-dataset  

---

## ⚙️ Methodology  

### 🔹 Lazy Classification  
- Used **LazyClassifier (lazypredict)**  
- Automatically trained multiple models  
- Compared performance efficiently  

### 🔹 Models Applied  
- K-Nearest Neighbors (KNN)  
- Decision Tree Classifier  

---

## 🎛️ Parameter Tuning  

- **KNN:** Optimized value of `k` using cross-validation  
- **Decision Tree:** Tuned `max_depth` parameter  

👉 Goal: Improve accuracy and generalization  

---

## 📊 Model Evaluation  

- Train/Test Split  
- Cross-Validation  
- Metrics:
  - Accuracy  
  - Confusion Matrix  
  - ROC Curve  
  - Learning Curve  

---

## 📈 Results  

| Model           | Performance |
|----------------|------------|
| KNN            | High Accuracy (Best Performing) |
| Decision Tree  | Competitive Performance |

> KNN performed best after parameter tuning.

---

## 💡 Key Insights  

- Lazy learning methods are effective for **dynamic datasets**  
- Parameter tuning significantly improves performance  
- Simple models like KNN can outperform complex models when optimized  

---

## 🛠️ Tech Stack  

- Python  
- Scikit-learn  
- Pandas  
- NumPy  
- Matplotlib  

---

## ▶️ How to Run  

```bash
git clone https://github.com/Taqiali5/OSDA_BigHome_Assingment.git
cd OSDA_BigHome_Assingment
pip install -r requirements.txt
python main.py
