\# Heart Disease Prediction using Logistic Regression



\## 📌 Project Overview

This project focuses on building a binary classification machine learning model to predict the presence of heart disease using patient clinical data. Logistic Regression was chosen due to its interpretability and effectiveness in medical decision-making scenarios.



---



\## 🧠 Problem Statement

Heart disease is one of the leading causes of death worldwide. Early detection can help in timely medical intervention. The goal of this project is to predict whether a patient has heart disease based on medical attributes.



---



\## 📂 Dataset

The dataset contains clinical features such as:

\- Age

\- Sex

\- Chest pain type

\- Resting blood pressure

\- Cholesterol level

\- Maximum heart rate

\- ECG results



(Target variable: presence or absence of heart disease)



---



\## ⚙️ Methodology

1\. Data loading and exploration  

2\. Handling missing values using mean imputation  

3\. Feature selection and scaling  

4\. Model training using Logistic Regression  

5\. Model evaluation using confusion matrix, precision, recall, and F1 score  



---



\## 📊 Model Evaluation

In healthcare problems, false negatives can be critical. Therefore, accuracy alone is not sufficient.



\- \*\*Precision\*\*: How many predicted positives are actually positive  

\- \*\*Recall\*\*: How many actual positives are correctly identified  

\- \*\*F1 Score\*\*: Harmonic mean of precision and recall  

\- \*\*Confusion Matrix\*\*: Visualizes correct and incorrect predictions  



F1 score was used as the primary metric to balance precision and recall.



---



\## 📈 Sigmoid Function

Logistic Regression uses the sigmoid function to convert linear outputs into probabilities between 0 and 1, helping in binary classification decisions.



---



\## 🧪 Sample Prediction

The model can take patient medical values as input and predict whether the patient is likely to have heart disease.



---



\## 🛠️ Tech Stack

\- Python

\- Pandas

\- NumPy

\- Scikit-learn

\- Matplotlib



---
## 📊 Visual Results

### Confusion Matrix
The confusion matrix helps analyze true positives, false positives, false negatives, and true negatives, which is crucial in healthcare applications.

![Confusion Matrix](images/Confusion_Matrix.png)

### Sigmoid Curve
The sigmoid function maps linear model outputs to probabilities between 0 and 1, forming the basis of Logistic Regression.

![Sigmoid Curve](images/Sigmoid_Curve.png)

---



\## 📌 Conclusion

This project demonstrates an end-to-end machine learning pipeline with a focus on model interpretability, correct evaluation metrics, and real-world healthcare relevance.



---



\## 👩‍💻 Author

\*\*Sritama Kolay\*\*  

Second-year CSE student | Machine Learning Enthusiast



