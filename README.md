📊 Machine Learning Model Comparison Project

A collaborative project that evaluates and compares multiple Machine Learning algorithms across different datasets and test sizes to analyze performance.

🎯 Objective

The main goal of this project is to:

Compare performance of multiple ML models
Analyze accuracy across different test sizes (0.2, 0.4, 0.6)
Understand behavior of different algorithms
Visualize results using output graphs/screenshots

👥 Team Contributions
Member	Algorithms Used
Rajeshwari	CatBoost, Decision Tree, Gradient Boosting, KNN
Hema	LDA, Logistic Regression, LightGBM, SVM
Varsha	MLP, Naive Bayes, QDA, SVM
Akshaya	ADA (AdaBoost), RFC (Random Forest), XGB (XGBoost)

🧠 Algorithms Used
🔹 Ensemble Methods
Random Forest (RFC)
AdaBoost (ADA)
Gradient Boosting (GBC)
XGBoost (XGB)
CatBoost
🔹 Linear Models
Logistic Regression (LG)
Linear Discriminant Analysis (LDA)
🔹 Neural & Probabilistic
MLP (Neural Network)
Naive Bayes (NB)
QDA
🔹 Others
Support Vector Machine (SVM)
K-Nearest Neighbors (KNN)
Decision Tree Classifier (DTC)
📂 Project Structure
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
        └── Result images (graphs/screenshots)
⚙️ Working Methodology
Step 1: Data Splitting

Dataset is split into:

80% Train / 20% Test
60% Train / 40% Test
40% Train / 60% Test
Step 2: Model Training

Each algorithm is trained separately on training data.

Step 3: Prediction

Models predict outcomes on test data.

Step 4: Evaluation

Performance is evaluated using:

Accuracy
Confusion Matrix
Graphical outputs (stored as images)
📈 Workflow Diagram
          ┌───────────────┐
          │   Dataset     │
          └──────┬────────┘
                 │
     ┌───────────▼───────────┐
     │ Train-Test Split      │
     │ (0.2 / 0.4 / 0.6)     │
     └───────────┬───────────┘
                 │
        ┌────────▼────────┐
        │ Train Model     │
        └────────┬────────┘
                 │
        ┌────────▼────────┐
        │ Prediction      │
        └────────┬────────┘
                 │
        ┌────────▼────────┐
        │ Evaluation      │
        │ (Accuracy etc.) │
        └────────┬────────┘
                 │
        ┌────────▼────────┐
        │ Result Images   │
        └─────────────────┘
📸 Results & Outputs

Each folder contains output screenshots like:

Accuracy graphs
Model performance comparison
Confusion matrices
Example Structure:
ADA/
 └── test_size=0.2/
     └── Akshaya ADA 0.2.jpeg

👉 These images represent how each model performs under different data splits.

🔍 Key Observations (You can modify based on your findings)
Ensemble models (Random Forest, XGBoost) generally perform better
Performance varies with test size
SVM and Logistic Regression perform well on structured data
Neural networks (MLP) require more tuning
🎓 Academic Value

This project helps in understanding:

Model comparison techniques
Bias-variance tradeoff
Effect of training data size
Real-world ML evaluation
🚀 Future Enhancements
Add code implementation (currently only results are present)
Create a unified dashboard for comparison
Add metrics like F1-score, ROC curves
Automate result generation
📜 Conclusion

This project provides a structured comparison of multiple machine learning algorithms under varying conditions, helping in selecting the best model for a given dataset.
