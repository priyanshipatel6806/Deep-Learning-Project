# Deep Learning Applications on Energy Efficiency and Credit Card Fraud Detection

**Course:** INFO-6146 – TensorFlow & Keras with Python  
**Prepared by:** Priyanshi Patel

---

## Project Overview
This project applies **deep learning models** to two real-world machine learning tasks:  

1. **Regression Task – Energy Efficiency Dataset**  
   - Predicting heating load of buildings using architectural and environmental features.  
   - Models: Linear Regression (baseline) vs. Deep Neural Network (DNN).  

2. **Classification Task – Credit Card Fraud Detection**  
   - Identifying fraudulent transactions from highly imbalanced financial data.  
   - Models: Logistic Regression (baseline) vs. Deep Neural Network (DNN).  

The project compares **baseline ML models** with **deep learning models**, covering all stages of the ML pipeline:  
- Data preprocessing  
- Model design  
- Hyperparameter tuning  
- Regularization & early stopping  
- Evaluation with appropriate metrics  

---

## Key Results
### Regression (Energy Efficiency)
- **Linear Regression:** MSE = 9.15, MAE = 2.18, R² = 0.912  
- **Neural Network:** MSE = 7.25, MAE = 1.98, R² = 0.931  

The neural network captured nonlinear patterns better and improved accuracy.  

---

### Classification (Fraud Detection)
- **Logistic Regression:** AUC = 0.972, Precision = 0.06, Recall = 0.92, F1 = 0.11  
- **Neural Network:** AUC = 0.978, Precision = 0.82, Recall = 0.86, F1 = 0.84  

The deep learning model balanced **precision and recall**, drastically reducing false positives while catching most fraud cases.  
