<h1 align="center">🪨 Rock vs Mine Prediction using Logistic Regression</h1>

<p align="center">
A simple binary classification project using sonar signals to identify whether the object is a <strong>rock</strong> or a <strong>mine</strong>. Built with Python and Scikit-learn.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.x-blue?logo=python" />
  <img src="https://img.shields.io/badge/Model-Logistic%20Regression-brightgreen" />
  <img src="https://img.shields.io/badge/License-MIT-green.svg" />
</p>

---

## 🧠 Problem Statement

Using sonar signal readings, predict whether an object in the water is a **mine** (dangerous) or a **rock** (harmless).  
This classification task is useful in military, marine exploration, and autonomous navigation systems.

---

## 📊 Dataset Details

- **Name:** Sonar Dataset  
- **Source:** [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/connectionist+bench+sonar+mines+vs+rocks)  
- **Instances:** 208 samples  
- **Features:** 60 numerical sound frequency attributes  
- **Label:**  
  - `M` = Mine  
  - `R` = Rock

---

## 🚀 Workflow Overview

1. **Import Libraries** – Load necessary Python packages  
2. **Load Dataset** – Read sonar data into a DataFrame  
3. **Explore Data** – Examine dataset structure and label distribution  
4. **Split Features and Labels** – Separate input features and target labels  
5. **Train-Test Split** – Divide data (90% train, 10% test) with stratification  
6. **Train Model** – Fit Logistic Regression classifier on training data  
7. **Evaluate Model** – Assess accuracy on training and test sets  
8. **Predict** – Use trained model to classify new sonar samples  

---

## 🧪 Why Logistic Regression?

We chose **Logistic Regression** because:
- The problem is binary classification (`M` vs `R`)
- The dataset is relatively small
- Logistic Regression is interpretable and quick to train
- Good baseline model for linearly separable data

---

## 📈 Model Accuracy

| Dataset   | Accuracy |
|-----------|----------|
| Training  | ~83%     |
| Testing   | ~76%     |

_(Exact values may vary depending on random_state)_

---

## 💡 Sample Input & Output

```python
input_data = (
    0.0303, 0.0353, 0.1002, ..., 0.0015  # 60 sonar readings
)
```

Output:

```
Prediction: M
The object is a Mine.
```

---

## 📦 Installation & Setup

```bash
git clone https://github.com/Toshaksha/Machine-Learning.git
cd rock_vs_mine_prediction
pip install -r requirements.txt
```

---

## 📝 How to Use
- Open `rock_vs_mine_prediction.ipynb` in Jupyter Notebook or Google Colab.
- Run the cells step-by-step to train the model and test predictions.
- Use the provided function to input custom sonar data and get predictions.

---

## 📂 Files & Structure

```
rock-vs-mine-prediction/
│
├── sonar_data.csv                    # Dataset file
├── Rock_vs_Mine_Prediction.ipynb     # Jupyter/Colab notebook with model and prediction
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

**Toshaksha** – [Github Profile](https://github.com/Toshaksha)  


Feel free to connect or reach out!

---
⭐ **If you found this project helpful, consider giving it a star!**

