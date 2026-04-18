# 📊 Machine Learning Model Comparison Project

> 🚀 A comprehensive study and comparison of multiple Machine Learning algorithms across different data splits to evaluate performance and behavior.

---

## 🎯 Objective

This project aims to:

✔ Compare multiple Machine Learning models  
✔ Analyze performance using different test sizes (0.2, 0.4, 0.6)  
✔ Understand algorithm behavior under varying data conditions  
✔ Visualize results using graphs and output images  

---

## 👥 Team Contributions

| 👤 Member      | ⚙️ Algorithms Used |
|--------------|------------------|
| **Rajeshwari** | CatBoost, Decision Tree, Gradient Boosting, KNN |
| **Hema**       | LDA, Logistic Regression, LightGBM, SVM |
| **Varsha**     | MLP, Naive Bayes, QDA, SVM |
| **Akshaya**    | AdaBoost (ADA), Random Forest (RFC), XGBoost (XGB) |

---

## 🧠 Algorithms Covered

### 🔹 Ensemble Learning
- Random Forest (RFC)
- AdaBoost (ADA)
- Gradient Boosting (GBC)
- XGBoost (XGB)
- CatBoost

### 🔹 Linear Models
- Logistic Regression (LG)
- Linear Discriminant Analysis (LDA)

### 🔹 Neural & Probabilistic Models
- MLP (Neural Network)
- Naive Bayes (NB)
- Quadratic Discriminant Analysis (QDA)

### 🔹 Other Models
- Support Vector Machine (SVM)
- K-Nearest Neighbors (KNN)
- Decision Tree Classifier (DTC)

---

## 📂 Project Structure

DCN_PROJECT/
│
├── AKSHAYA/
│   ├── ADA/
│   ├── RFC/
│   └── XGB/
│
├── HEMA/
│   ├── LDA/
│   ├── LG/
│   ├── LGBM/
│   └── SVM/
│
├── RAJESHWARI/
│   ├── CAT/
│   ├── DTC/
│   ├── GBC/
│   └── KN/
│
├── VARSHA/
│   ├── MLP/
│   ├── NB/
│   ├── QDA/
│   └── SVM/
│
└── Each folder contains:
    └── test_size = 0.2 / 0.4 / 0.6
        └── Result Images

---

## ⚙️ Methodology

### 🔹 Step 1: Data Splitting
- 80% Train / 20% Test  
- 60% Train / 40% Test  
- 40% Train / 60% Test  

### 🔹 Step 2: Model Training
Each algorithm is trained independently using training data.

### 🔹 Step 3: Prediction
Models generate predictions on unseen test data.

### 🔹 Step 4: Evaluation Metrics
- Accuracy  
- Confusion Matrix  
- Visual Graph Outputs  

---

## 📈 Workflow

Dataset → Train-Test Split → Model Training → Prediction → Evaluation → Results

---

## 📸 Results & Outputs

Each algorithm folder contains:

- Accuracy Graphs  
- Confusion Matrices  
- Performance Visualizations  

Example:

ADA/
 └── test_size=0.2/
     └── Akshaya_ADA_0.2.jpeg

---

## 🔍 Key Insights

- Ensemble models generally perform better  
- Performance varies with test size  
- SVM and Logistic Regression perform well on structured data  
- Neural networks require tuning  

---

## 🎓 Academic Importance

This project demonstrates:

- Model comparison techniques  
- Bias vs Variance concept  
- Impact of training data size  
- Practical ML evaluation  

---

## 🚀 Future Improvements

- Add full source code  
- Build comparison dashboard  
- Include advanced metrics (F1-score, ROC curve)  
- Automate training and evaluation  

---

## 📜 Conclusion

This project provides a structured comparison of Machine Learning models to identify the most effective approach under different conditions.

---

