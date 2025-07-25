
<h1 align="center">🩺 Diabetes Prediction using Support Vector Machine (SVM)</h1>

<p align="center">
A binary classification machine learning project to predict whether a patient has diabetes based on health parameters such as glucose level, BMI, age, and more. Built with Python and Scikit-learn.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.x-blue?logo=python" />
  <img src="https://img.shields.io/badge/Model-Support%20Vector%20Machine-brightgreen" />
  <img src="https://img.shields.io/badge/License-MIT-green.svg" />
</p>

---

## 🧠 Problem Statement

Given health-related features of patients, predict whether they have diabetes (1) or not (0).  
This model helps in early detection and preventive healthcare management.

---

## 📊 Dataset Details

- **Name:** Pima Indian Diabetes Dataset  
- **Source:** [UCI Machine Learning Repository](https://www.kaggle.com/uciml/pima-indians-diabetes-database)  
- **Instances:** 768 samples  
- **Features:** 8 numerical health indicators (Pregnancies, Glucose, BloodPressure, SkinThickness, Insulin, BMI, DiabetesPedigreeFunction, Age)  
- **Label:**  
  - `0` = Non-Diabetic  
  - `1` = Diabetic  

---

## 🚀 Workflow Overview

1. **Import Libraries** – Load essential Python packages  
2. **Load & Explore Data** – Read dataset and examine basic stats  
3. **Separate Features & Labels** – Split inputs and target variable  
4. **Train-Test Split** – Stratified split into training and testing sets  
5. **Data Standardization** – Scale features for optimal model performance  
6. **Train SVM Model** – Fit a linear Support Vector Machine classifier  
7. **Evaluate Model** – Calculate accuracy on training and test data  
8. **Make Predictions** – Test model on new patient data  

---

## 🧪 Why Support Vector Machine (SVM)?

- Effective for binary classification problems  
- Performs well on small to medium datasets  
- Can find optimal decision boundaries with linear kernel  
- Robust to overfitting in high-dimensional spaces  

---

## 📈 Model Accuracy

| Dataset   | Accuracy |
|-----------|----------|
| Training  | ~78%     |
| Testing   | ~77%     |

_(Note: Accuracy may vary slightly based on random seed and scaling)_

---

## 💡 Sample Input & Output

```python
input_data = (4, 110, 92, 0, 0, 37.6, 0.191, 30)  # Patient features
````

Output:

```
Prediction: 1
Person is Diabetic.
```

---

## 📦 Installation & Setup

```bash
git clone https://github.com/Toshaksha/Machine-Learning.git
cd diabetes_prediction
pip install -r requirements.txt
```

---

## 📝 How to Use

* Open `diabetes_prediction.ipynb` in Jupyter Notebook or Google Colab.
* Run each cell sequentially to train the model and test predictions.
* Modify or input new patient data tuples to predict diabetes status.

---

## 📂 Files & Structure

```
diabetes-prediction-svm/
│
├── diabetes.csv                      # Dataset file
├── diabetes_prediction.ipynb         # Notebook with full code and predictions
├── requirements.txt                  # Python dependencies
└── README.md                         # Project documentation
```

---

## 🧰 Tech Stack

* Python 3.x
* NumPy
* Pandas
* Scikit-learn

---

## 👤 Author

**Toshaksha** – [GitHub Profile](https://github.com/Toshaksha)

Feel free to connect or reach out!

---

⭐ **If you found this project helpful, please consider giving it a star!**

---
