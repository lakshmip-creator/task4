# Logistic Regression Classifier (Task 4)

## 📌 Objective
Build a **binary classifier** using Logistic Regression and evaluate it with standard metrics.

## 🛠 Tools
- Python 3.x  
- Scikit-learn  
- Pandas  
- Matplotlib  
- NumPy  

## 📂 Dataset
Breast Cancer Wisconsin Dataset (`load_breast_cancer` from scikit-learn).  
- Target:  
  - `0` = Malignant  
  - `1` = Benign  

## 🚀 Steps
1. Load dataset  
2. Train/Test split + Standardize features  
3. Train Logistic Regression model  
4. Evaluate: Accuracy, Precision, Recall, Confusion Matrix, ROC-AUC  
5. Tune classification threshold  
6. Visualize **Confusion Matrix**, **ROC Curve**, **Sigmoid Function**  

## 📊 Results
- Accuracy: ~95%  
- ROC-AUC: ~0.99  
- Visualizations: Confusion Matrix, ROC Curve, Sigmoid Curve  

## ▶️ Run
```bash
git clone https://github.com/your-username/logistic-regression-classifier.git
cd logistic-regression-classifier
pip install -r requirements.txt
python logistic_regression_classifier.py
