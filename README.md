# ASSIGN_SAMPLING
# 💳 Sampling Assignment – Credit Card Fraud Detection

## 👩‍💻 Author  
**Ravneet Kaur**  
**Roll No: 102303943**

---

## 📌 Objective
The objective of this assignment is to study the importance of sampling techniques while working with imbalanced datasets and to analyze how different sampling strategies affect the performance of various machine learning models.

---

## 📂 Dataset
The dataset used is the **Credit Card Fraud Detection Dataset**, which is highly imbalanced.

- Class `0` → Legitimate Transactions  
- Class `1` → Fraudulent Transactions  

To address the class imbalance problem, the dataset was first converted into a **balanced dataset** using Random Undersampling.

---

## 🔍 Sampling Techniques Used
The following sampling techniques were implemented:

1. Simple Random Sampling  
2. Systematic Sampling  
3. Stratified Sampling  
4. Cluster Sampling  
5. Bootstrap Sampling  

Additionally, **Cross-Validation** was used to evaluate model stability and consistency.

---

## 🤖 Machine Learning Models Used
Five machine learning models were trained and evaluated on each sampling technique:

- Logistic Regression  
- Decision Tree  
- Random Forest  
- Support Vector Machine (SVM)  
- K-Nearest Neighbors (KNN)  

---

## 📊 Experimental Results

| Model / Sampling | Simple Random | Systematic | Stratified | Cluster | Bootstrap |
|------------------|--------------|------------|------------|---------|-----------|
| Logistic Regression | 33.33% | 0.00% | 16.67% | 50.00% | 100.00% |
| Decision Tree | 66.67% | 0.00% | 66.67% | 0.00% | 100.00% |
| Random Forest | 66.67% | 33.33% | 33.33% | 100.00% | 83.33% |
| SVM | 50.00% | 33.33% | 16.67% | 50.00% | 100.00% |
| KNN | 50.00% | 33.33% | 16.67% | 50.00% | 100.00% |

> *All values represent accuracy in percentage (%).*

---

## 📈 Analysis & Discussion

- **Bootstrap Sampling** performed the best overall, delivering high accuracy for most models.
- **Cluster Sampling** worked exceptionally well with Random Forest but showed instability with simpler models.
- **Systematic Sampling** showed comparatively lower performance due to potential loss of class diversity.
- Ensemble models such as **Random Forest** were more robust to sampling variations compared to linear models.

---

## ✅ Conclusion
This study demonstrates that the choice of sampling technique plays a crucial role in model performance when dealing with imbalanced datasets.

- Bootstrap Sampling provided strong generalization.
- Stratified Sampling ensured balanced class representation.
- Ensemble methods proved more stable under different sampling strategies.

Proper sampling selection is essential for building reliable fraud detection systems.

---

## ▶️ How to Run the Project

1. Upload `Creditcard_data.csv` to Google Colab.
2. Open `sampling_assignment.ipynb`.
3. Run all cells sequentially.
4. The final accuracy comparison table will be generated automatically.

---

## 🛠 Technologies Used

- Python  
- Pandas  
- NumPy  
- Scikit-learn  
- Google Colab  

---

⭐ If you found this project helpful, feel free to give it a star!
