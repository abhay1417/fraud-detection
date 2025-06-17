# 🕵️‍♂️ Fraud Detection Using Machine Learning

# 🕵️‍♂️ Fraud Detection Using Machine Learning

This project uses a machine learning model to detect fraudulent financial transactions using transaction data such as amount, time, and customer/terminal IDs.

---

## 📁 Files Included

- `fraud_detection.ipynb` – Complete Colab notebook with code and outputs
- `Fraud_Detection_ipynb_.pdf` – Clean PDF version of the project notebook

---

## 📊 Dataset Overview

- Dataset was built by combining multiple `.pkl` files
- Final dataset contained over 1.7 million transactions
- Target column: `TX_FRAUD` (0 = genuine, 1 = fraud)
- Imbalanced data: Only ~0.84% were fraudulent

---

## 🧠 ML Model Used

- **Logistic Regression** with `class_weight='balanced'`
- Features used: `TX_AMOUNT`, `TX_TIME_SECONDS`, `TX_TIME_DAYS`
- Accuracy: ~54%
- Recall for fraud detection: ~60%

---

## 🛠️ Tools Used

- Python
- Pandas
- Scikit-learn
- Google Colab

---

## 👤 Author

**Abhay Ajay Palkar**  
Guided by: **Unified Mentor**

---

*Note: Full dataset not uploaded due to GitHub file size limit.*

