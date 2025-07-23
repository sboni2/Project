# 💼 Employee Salary Prediction

This project is a machine learning-based system that predicts whether an employee earns more than ₹50,000 (or \$50K) annually based on demographic and employment-related attributes. It also includes an interactive web application built using **Streamlit** that allows for both single and batch predictions.

---

## 📌 Problem Statement

Organizations often need to analyze employee data to make informed HR decisions such as identifying potential high earners. This project aims to solve this problem by developing a classification model that predicts salary class (`>50K` or `≤50K`) using inputs such as age, education, occupation, hours worked per week, and experience.

---

## 🚀 Features

* Interactive web app built with **Streamlit**
* Supports **real-time prediction** via manual input
* Allows **batch prediction** via CSV upload
* Compares multiple ML models (Logistic Regression, Random Forest, SVM, KNN, etc.)
* Includes **data cleaning, outlier handling, and label encoding**
* Deployed via **pyngrok** for live testing from Google Colab

---

## 📊 Dataset

* **Source**: [UCI Adult Income Dataset](https://archive.ics.uci.edu/ml/datasets/adult)
* The dataset includes attributes such as:

  * Age
  * Education
  * Occupation
  * Hours-per-week
  * Relationship
  * Gender
  * Capital Gain/Loss
  * Native Country
  * and more...

---

## 🧠 Machine Learning Models Used

* Logistic Regression
* Random Forest
* Support Vector Machine (SVM)
* K-Nearest Neighbors (KNN)
* Gradient Boosting

➡️ Best performing model: **Random Forest** with accuracy of \~86%.

---

## 🛠️ Tools and Technologies

* Python
* Pandas, Scikit-learn, Matplotlib
* Streamlit
* pyngrok (for deployment in Colab)
* Google Colab / VS Code
* joblib (for model serialization)

---

## 📦 Installation & Usage

### Clone the repository:

```bash
git clone https://github.com/yourusername/employee-salary-prediction.git
cd employee-salary-prediction
```

### Install dependencies:

```bash
pip install -r requirements.txt
```

### Run the app locally:

```bash
streamlit run app.py
```

> To run from Google Colab, ensure you install `pyngrok` and follow the ngrok tunnel setup.

---

## 🧪 Example Inputs

| Age | Education | Occupation      | Hours-per-week | Experience |
| --- | --------- | --------------- | -------------- | ---------- |
| 35  | Bachelors | Sales           | 40             | 10         |
| 42  | Masters   | Exec-managerial | 50             | 18         |

---

## 📷 Screenshots

> *(Insert images or gifs of your web UI, predictions, charts, etc.)*

---

## 📚 References

* UCI Machine Learning Repository – Adult Dataset
* Scikit-learn documentation
* Streamlit documentation
* Stack Overflow

---


