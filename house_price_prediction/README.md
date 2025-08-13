
<h1 align="center">🏠 Houston Housing Price Prediction using Random Forest</h1>

<p align="center">
A regression machine learning project to predict home prices in Houston using features like location, property details, and Zillow estimates. Built with Python and Scikit-learn.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.x-blue?logo=python" />
  <img src="https://img.shields.io/badge/Model-Random%20Forest%20Regressor-green" />
  <img src="https://img.shields.io/badge/Type-Regression-blueviolet" />
</p>

---

## 🧠 Problem Statement

Predict the **market price** (`unformattedPrice`) of residential properties in the Houston area using real estate listing data.  
This can support buyers, sellers, and agents in estimating property value based on home features.

---

## 📊 Dataset Details

- **Name:** Houston Housing Market 2024  
- **Source:** [Kaggle - datadetective08](https://www.kaggle.com/datasets/datadetective08/houston-housing-market-2024)  
- **Records:** ~15,000+ homes  
- **Features:** Street address, Zillow Zestimate, area, beds, baths, listing status, image data, etc.  
- **Target:**  
  - `unformattedPrice` = Actual listed price of the property  

---

## 🚀 Workflow Overview

1. **Import Libraries** – Load essential Python packages  
2. **Load & Explore Data** – Understand data shape and structure  
3. **Data Cleaning** – Drop irrelevant or missing-value-heavy columns  
4. **Missing Value Imputation** – Fill missing values using median/mode  
5. **Feature Encoding** – Convert categorical variables using One-Hot Encoding  
6. **Train-Test Split** – Randomly split dataset for training and testing  
7. **Model Building** – Use Random Forest Regressor for price prediction  
8. **Evaluate Performance** – Check MAE (Mean Absolute Error) on test set  
9. **Feature Importance** – Check top influencing variables  

---

## 🌲 Why Random Forest?

- Handles non-linear relationships well  
- Robust to outliers and overfitting  
- Can rank feature importance  
- Works well with high-dimensional structured datasets  

---

## 📈 Model Performance

| Metric       | Value         |
|--------------|---------------|
| Test MAE     | ~$111,063     |
| Avg. Price   | ~$521,595     |
| % Error      | ~21.3%        |

> 📌 *This is reasonable for a first-pass model in real estate, but performance can be improved further with hyperparameter tuning, additional feature engineering, and removing noisy attributes.*

---

## 💡 Sample Features Used

- `zestimate`  
- `area`, `beds`, `baths`  
- `address`, `price`, `statusType`, etc. (after one-hot encoding)

---

## 🏗 Project Structure

```
houston-housing-price-prediction/
│
├── houston_housing market 2024_light.json          # Dataset file
├── housing_price_prediction.ipynb                  # Notebook with full model workflow
└── README.md                                       # Project documentation
```


---

## 🧰 Tech Stack

- Python 3.x  
- Pandas  
- NumPy  
- Scikit-learn  

---

## 👤 Author

**Toshaksha** – [GitHub Profile](https://github.com/Toshaksha)

---

⭐ *If you found this project helpful, please consider giving it a star!*
