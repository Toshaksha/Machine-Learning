<h1 align="center">📰 Fake News Detection using Logistic Regression</h1>

<p align="center">
A binary text classification machine learning project that detects whether a news article is real or fake using Natural Language Processing (NLP) techniques and Logistic Regression.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.x-blue?logo=python" />
  <img src="https://img.shields.io/badge/Model-Logistic%20Regression-brightgreen" />
  <img src="https://img.shields.io/badge/NLP-TFIDF%20%2B%20Stemming-orange" />
  <img src="https://img.shields.io/badge/License-MIT-green.svg" />
</p>

---

## 🧠 Problem Statement

Given a dataset of real and fake news articles, build a model that can classify new/unseen news as either real or fake based on its textual content.

---

## 📊 Dataset Details

- **Sources:**  
  - `True.csv` – Contains real news articles  
  - `Fake.csv` – Contains fake news articles  
- **Columns Used:** `title`, `text`, `subject`
- **Labeling:**  
  - `1` = Real news  
  - `0` = Fake news  
- **Content Field:** All three columns are combined into one text feature before preprocessing.

---

## 🚀 Workflow Overview

1. **Import Libraries** – Load all essential Python libraries
2. **Data Collection** – Load both CSVs directly from ZIP files
3. **Data Cleaning & Labeling** – Assign labels and combine content
4. **Text Preprocessing** – Apply stemming and stopword removal
5. **TF-IDF Vectorization** – Convert cleaned text into numerical vectors
6. **Train-Test Split** – Split the data for training and evaluation
7. **Model Training** – Train a Logistic Regression classifier
8. **Evaluation** – Assess model accuracy on both train/test sets
9. **Prediction System** – Test the model with real examples

---

## 🛠 Techniques Used

- **Natural Language Processing (NLP)**  
  - Stopwords removal  
  - Stemming using `PorterStemmer`  
  - TF-IDF Vectorization with unigrams and bigrams  
- **Machine Learning**  
  - Logistic Regression (for binary classification)  
- **Tools**  
  - Pandas, Scikit-learn, NLTK

---

## 📈 Model Accuracy

| Dataset   | Accuracy |
|-----------|----------|
| Training  | ~99.5%   |
| Testing   | ~99.2%   |

✔️ Indicates excellent generalization.

---

## 💬 Example Prediction

```python
# Predicting on one news article
X_new = X_test[0]
prediction = model.predict(X_new)

if prediction[0] == 0:
    print("News is Fake")
else:
    print("News is Real")
````

---

## 📦 Installation & Setup

```bash
git clone https://github.com/Toshaksha/fake_news_prediction.git
cd fake_news_prediction
pip install -r requirements.txt
```

---

## 📝 How to Use

* Upload `True.csv.zip` and `Fake.csv.zip` to your working directory (Colab recommended).
* Run the notebook `fake_news_prediction.ipynb`.
* Follow each cell step-by-step to preprocess, train, and evaluate the model.
* You can modify test examples or use new text for prediction.

---

## 📂 Project Structure

```
fake-news-detection/
│
├── Fake.csv.zip                     # Zip file with fake news
├── True.csv.zip                     # Zip file with real news
├── fake_news_prediction.ipynb       # Notebook with code and output
├── requirements.txt                 # Python dependencies
└── README.md                        # Project documentation
```

---

## ⚙️ Tech Stack

* Python 3.x
* Pandas
* Scikit-learn
* NLTK (for text preprocessing)
* tqdm (for progress bar)

---

## 👤 Author

**Toshaksha** – [GitHub Profile](https://github.com/Toshaksha)

---

⭐ **If this project helped you, please give it a ⭐ star on GitHub!**


---
