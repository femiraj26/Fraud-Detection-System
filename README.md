# 🚨 Fraud Detection System

## 📌 Project Goal
The goal of this project is to **detect fraudulent transactions in financial data** using both **anomaly detection** and **supervised classification techniques**.

---

## ⚙️ Approach
1. **Dataset**
   - Synthetic dataset created using `sklearn.datasets.make_classification`
   - Highly imbalanced: only 2% fraud cases (to simulate real-world transactions)

2. **Preprocessing**
   - Standardization of features
   - Handling class imbalance with **SMOTE (Synthetic Minority Oversampling Technique)**

3. **Models Used**
   - **Isolation Forest** (Unsupervised anomaly detection)
   - **Logistic Regression** (Supervised classification model)

4. **Evaluation Metrics**
   - Precision, Recall, F1-score
   - ROC-AUC Score
   - Confusion Matrix & ROC Curves

---

## 📊 Results
- **Isolation Forest** detects anomalies without labeled data.
- **Logistic Regression + SMOTE** performs well on imbalanced classification tasks.
- ROC curves and confusion matrices demonstrate performance trade-offs.

---

## 🚀 How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/fraud-detection-system.git
   cd fraud-detection-system
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Open the Jupyter Notebook / Google Colab file:
   ```bash
   FRAUD_DETECTION_SYSTEM_POLISHED.ipynb
   ```

4. Run all cells to train and evaluate the fraud detection models.

---

## 📦 Requirements
- Python 3.x
- numpy
- pandas
- scikit-learn
- imbalanced-learn
- matplotlib
- seaborn

(Also included in `requirements.txt`)

---

## 📈 Visualizations
### ROC Curve Example
![ROC Curve](images/roc_curve.png)

### Confusion Matrix Example
![Confusion Matrix](images/confusion_matrix.png)

---

## 🏁 Conclusion
- Fraud detection is a **highly imbalanced classification problem**.
- **SMOTE** helps balance the dataset for better supervised learning.
- Combining **unsupervised anomaly detection (Isolation Forest)** and **supervised classification (Logistic Regression)** makes the system more robust.
- This notebook serves as a **template for real-world financial fraud detection projects** and can be extended with deep learning models (e.g., Autoencoders).

---
