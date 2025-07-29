# 📊 Salary Prediction using Gaussian & Multinomial Naive Bayes

This project implements two types of **Naive Bayes classifiers**—Gaussian and Multinomial—on the **Adult Census Income dataset** to predict whether a person's salary exceeds \$50K/year.

---

## 🧠 Problem Statement

Given a dataset of personal attributes such as:

- Age, Education, Workclass, Occupation, etc.

The goal is to predict:

- **Target Variable**: `salary`  
  With values: `<=50K` or `>50K`

---

## 📂 Files

- `Gaussian_Multinomial.ipynb`: Full implementation using scikit-learn
- `data/adult.data`: Training set
- `data/adult.test`: Test set

---

## 🔍 Algorithms Implemented

- **Gaussian Naive Bayes** (for continuous features)
- **Multinomial Naive Bayes** (for categorical features)

Both models are evaluated using accuracy on the test set.

---

## ⚙️ How to Run

1. Clone the repository:
```bash
git clone https://github.com/yourusername/naive-bayes-salary-prediction.git
cd naive-bayes-salary-prediction

Open the notebook:

jupyter notebook Gaussian_Multinomial.ipynb

## 📈 Results
Classifier	Test Accuracy
Gaussian Naive Bayes	75.43%
Multinomial Naive Bayes	81.46%

## 📊 Dataset Source
The dataset is publicly available from the UCI Machine Learning Repository.

## 🧹 Preprocessing Steps
Missing value handling (replace '?')

Encoding categorical features (LabelEncoding / OneHot)

Normalizing numeric features (for Gaussian NB)

Matching test and train feature spaces

## 📄 License
This project is licensed under the MIT License.

## 🙋‍♂️ Author
Manjul Mayank
