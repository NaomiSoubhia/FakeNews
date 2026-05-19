

# 📰 Fake News Detection (JupyterLab Project)

## 📌 Overview

This project implements a **Fake News Detection system** using **machine learning and natural language processing (NLP)** techniques in **JupyterLab**.

The goal is to classify news articles as **real or fake** based on their textual content by following a complete ML workflow:

* Data preprocessing
* Feature extraction
* Model training
* Evaluation

---

## 🎥 Tutorial Reference

This project was developed by following a step-by-step tutorial:

[Fake News Detection Using Machine Learning (Python Project)](https://glasp.co/youtube/U6ieiJAhXQ4?utm_source=chatgpt.com)

The video demonstrates how to:

* Build a fake news classifier using Python
* Apply NLP techniques
* Train and evaluate machine learning models

---

## 🚀 Features

* Full **machine learning pipeline**
* Text cleaning and preprocessing
* TF-IDF vectorization
* Classification models (e.g., Logistic Regression / Naive Bayes)
* Model evaluation (accuracy, confusion matrix)
* Interactive workflow in **JupyterLab**

---

## 🛠️ Tech Stack

* Python
* JupyterLab
* Pandas
* NumPy
* Scikit-learn
* (Optional) NLTK / spaCy

---

## 📂 Project Structure

```
FakeNews/
│
├── FakeNews.ipynb        # Main notebook
├── data/                 # Dataset (if included)
├── requirements.txt      # Dependencies
└── README.md             # Documentation
```

---

## ⚙️ Installation

### 1. Clone the repository

```bash
git clone https://github.com/NaomiSoubhia/FakeNews.git
cd FakeNews
```

### 2. Create virtual environment

```bash
python -m venv venv
source venv/bin/activate   # Mac/Linux
venv\Scripts\activate      # Windows
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

---

## ▶️ Running the Project (JupyterLab)

Start JupyterLab:

```bash
jupyter lab
```

Open:

```
FakeNews.ipynb
```

Run all cells to:

* Load data
* Train model
* Evaluate results
* Make predictions

---

## 📊 Machine Learning Workflow

1. **Data Loading**

   * Import labeled dataset of news articles

2. **Preprocessing**

   * Remove stopwords, punctuation
   * Normalize text

3. **Feature Engineering**

   * Convert text into vectors using TF-IDF

4. **Model Training**

   * Train classification model

5. **Evaluation**

   * Accuracy
   * Confusion matrix
   * Precision & Recall

---

## 📈 Results

* Successfully classifies fake vs real news
* Performance depends on dataset quality and preprocessing

---

## 💡 Future Improvements

* Use deep learning (LSTM, BERT)
* Deploy as a web app (Flask / Streamlit)
* Add real-time prediction API
* Improve dataset size and quality

---

## 🤝 Contributing

Contributions are welcome!
Feel free to open issues or submit pull requests.

---

## 📜 License

MIT License

---

## 👩‍💻 Author

Naomi Soubhia Doi


