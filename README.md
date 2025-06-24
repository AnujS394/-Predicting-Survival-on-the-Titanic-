# 🚢 Titanic Survival Prediction – Machine Learning Project

[![Python](https://img.shields.io/badge/Python-3.9%2B-blue.svg)](https://www.python.org/)
[![License: MIT](https://img.shields.io/badge/license-MIT-green.svg)](LICENSE)

This project presents a supervised machine learning model that predicts whether a passenger survived the Titanic disaster. It uses logistic regression and includes all steps from data cleaning and preprocessing to training and evaluation.

---

## 📁 Repository Structure

titanic-survival-prediction/
│
├── titanic training (1).ipynb # Main Jupyter Notebook
├── titanic_confusion_matrix.png # Output image of confusion matrix
├── README.md # Project documentation
└── data/ # (Optional) for dataset files


---

git clone https://github.com/your-username/titanic-survival-prediction.git
cd titanic-survival-prediction



---

## 📌 Features

- Data cleaning & preprocessing
- Feature selection
- Train-test split
- Logistic Regression model
- Evaluation metrics:
  - Accuracy
  - Confusion matrix
  - Classification report

---


## outcome

          precision    recall  f1-score   support

       Dead       0.83      0.86      0.84       110
   Survived       0.77      0.72      0.74        69

    accuracy                           0.81       179




	PassengerId	Survived	Pclass	Name	Sex	Age	SibSp	Parch	Ticket	Fare	Cabin	Embarked
0	1	0	3	Braund, Mr. Owen Harris	male	22.0	1	0	A/5 21171	7.2500	NaN	S
1	2	1	1	Cumings, Mrs. John Bradley (Florence Briggs Th...	female	38.0	1	0	PC 17599	71.2833	C85	C
2	3	1	3	Heikkinen, Miss. Laina	female	26.0	0	0	STON/O2. 3101282	7.9250	NaN	S
3	4	1	1	Futrelle, Mrs. Jacques Heath (Lily May Peel)	female	35.0	1	0	113803	53.1000	C123	S
4	5	0	3	Allen, Mr. William Henry	male	35.0	0	0	373450	8.0500	NaN	S






![image](https://github.com/user-attachments/assets/c27b9518-16ae-48ac-87b1-b71573c50d17)
![survival by passenger class](https://github.com/user-attachments/assets/4b0d4ebf-070a-41a4-93bd-92405ada02a3)
![Screenshot 2025-06-24 210044](https://github.com/user-attachments/assets/b9887bf1-e2d3-4ff5-aa30-4eed40f7f534)

![image](https://github.com/user-attachments/assets/7b0636df-a321-406a-a42a-e7d30aa4a032)




## 🚀 How to Run

### 🔧 Requirements

Install dependencies:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter


