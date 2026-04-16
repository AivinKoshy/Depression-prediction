# 🧠 Depression Prediction for College Students

This is a simple machine learning project that predicts whether a college student may be experiencing depression based on various factors such as age, BMI, PHQ score, and more.

---

## 📌 Features

* Uses multiple machine learning models:

  * K-Nearest Neighbors
  * Decision Tree
  * Logistic Regression
  * Naive Bayes
  * Random Forest
* Compares performance using:

  * Accuracy
  * Classification Report
  * Confusion Matrix
* Allows user input for real-time prediction

---

## 📂 Project Structure

* `main.py` — contains all code for:

  * Data loading and preprocessing
  * Model training
  * Evaluation
  * User input prediction

---

## ⚙️ Requirements

Install the required libraries before running:

```bash
pip install pandas numpy scikit-learn
```

---

## ▶️ How to Run

1. Make sure your dataset is available and update the file path in the script if needed.
2. Run the Python file:

```bash
python main.py
```

3. Enter the requested values when prompted.

---

## 🧪 Input Parameters

You will be asked to enter:

* School Year
* Age
* Gender (0 = Female, 1 = Male)
* BMI
* PHQ Score
* Suicidal (0 = No, 1 = Yes)
* Depression Treatment (1 = Yes, 0 = No)
* Epworth Score

---

## 📊 Output

The program will:

* Train multiple models
* Display evaluation metrics for each model
* Predict depression using Logistic Regression
* Output: `YES` or `NO`

---

## ⚠️ Notes

* Logistic Regression gave the best results in this implementation.
* This project is for educational purposes only and should not be used for real medical diagnosis.

---
