# KNN-From-Scratch
"ML models implemented from scratch using NumPy and Pandas only"


🩺 KNN Classifier from Scratch – Diabetes Prediction

📌 Introduction

This project implements the K-Nearest Neighbors (KNN) algorithm from scratch (without sklearn classifiers) to predict diabetes using the PIMA Indians Diabetes Dataset.

KNN is a lazy learner: it predicts by finding the closest neighbors in the training set using Euclidean distance and applying majority voting.


---

📊 Dataset

Source: PIMA Indians Diabetes Dataset

Features: Glucose, Blood Pressure, BMI, Age, etc.

Target (Outcome):

0 → Non-Diabetic

1 → Diabetic




---

🧮 Key Formulas

Distance (Euclidean)


$$d(x, y) = \sqrt{\sum_{i=1}^{n} (x_i - y_i)^2}$$

Accuracy


$$\text{Accuracy} = \frac{TP + TN}{TP + TN + FP + FN}$$

Precision


$$\text{Precision} = \frac{TP}{TP + FP}$$

Recall


$$\text{Recall} = \frac{TP}{TP + FN}$$

F1-score


$$F1 = 2 \cdot \frac{\text{Precision} \cdot \text{Recall}}{\text{Precision} + \text{Recall}}$$


---

📈 Results & Visualizations

Confusion Matrix plotted for model evaluation.

Accuracy:-69%





---

🚀 How to Run

pip install numpy pandas matplotlib seaborn scikit-learn
python knn_from_scratch.py


---

✅ Conclusion

KNN works well but is sensitive to class imbalance and choice of k.

Class 1 (Diabetic) is harder to classify due to fewer samples and overlapping features.

Best k found using F1-score optimization.



---
