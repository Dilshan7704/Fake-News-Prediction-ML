# 📰 Fake News Classification using Machine Learning

<div align="center">

![Python](https://img.shields.io/badge/Python-3.10+-blue?style=for-the-badge&logo=python)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-ML-orange?style=for-the-badge&logo=scikitlearn)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-black?style=for-the-badge&logo=pandas)
![NumPy](https://img.shields.io/badge/NumPy-Numerical%20Computing-blue?style=for-the-badge&logo=numpy)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-green?style=for-the-badge)
![Seaborn](https://img.shields.io/badge/Seaborn-EDA-purple?style=for-the-badge)
![Status](https://img.shields.io/badge/Project-Completed-success?style=for-the-badge)

### 🚀 Machine Learning Project for Detecting Fake and Real News Articles

Detecting fake news using **Natural Language Processing (NLP)**, **TF-IDF Vectorization**, and **Logistic Regression Classification**.

</div>

---

# 📌 Project Overview

Fake news has become one of the biggest challenges in the digital era. This project focuses on building a Machine Learning model capable of automatically classifying news articles as **Fake** or **Real** based on textual content.

The project includes:

✔ Data Cleaning & Preprocessing

✔ Exploratory Data Analysis (EDA)

✔ Text Feature Engineering

✔ TF-IDF Vectorization

✔ Logistic Regression Classification

✔ Model Evaluation

✔ News Prediction System

---

# 🗂️ Project Structure

```bash
FAKE-NEWS-PREDICTION/
│
├── 📁 Data set/
│   └── WELFake_Dataset_1000.csv
├── 📁 src/
│   └── code.ipynb
│
├── 📄 requirements.txt
├── 📄 .gitignore
└── 📄 README.md
```

---

# ⚙️ Technologies Used

| Technology | Purpose |
|------------|----------|
| Python | Programming Language |
| Pandas | Data Manipulation |
| NumPy | Numerical Computing |
| Matplotlib | Data Visualization |
| Seaborn | Statistical Visualization |
| Scikit-Learn | Machine Learning |
| Regex | Text Cleaning |
| NLP | Text Processing |

---

# 📊 Exploratory Data Analysis (EDA)

Extensive Exploratory Data Analysis was performed to understand the characteristics of fake and real news articles.

### 🔍 EDA Includes

- Missing Value Analysis
- Dataset Balancing
- Class Distribution Analysis
- Text Length Analysis
- Content Length Comparison
- Statistical Summaries

---

# 📈 Visualizations

The project includes multiple visualizations such as:

✅ Real vs Fake News Countplot

✅ Content Length Distribution

✅ Word Count Analysis

✅ News Length Boxplots

---

# 🧹 Text Preprocessing

The following preprocessing techniques were applied:

- Convert text to lowercase
- Remove URLs
- Remove HTML tags
- Remove unwanted symbols
- Normalize whitespace
- Combine title and article content

---

# 🤖 Machine Learning Model

The following Machine Learning pipeline was implemented:

### TF-IDF Vectorizer

- max_features = 50000
- ngram_range = (1,2)
- stop_words = english
- min_df = 2

### Classification Model

✅ Logistic Regression

---

# 🏆 Model Performance

The model was evaluated using:

- Accuracy Score
- Precision
- Recall
- F1 Score
- Classification Report
- Confusion Matrix

---

# 🔮 News Prediction System

A custom prediction function was implemented to classify news articles as:

- ✅ Real News
- 🚨 Fake News

```python
predict_news(title, text)
```

---

# 📚 Dataset Information

Dataset used for this project:

🔗 https://www.kaggle.com/datasets/saurabhshahane/fake-news-classification

### Dataset Name

WELFake Dataset

### Target Variable

| Label | Meaning |
|---------|---------|
| 0 | Fake News |
| 1 | Real News |

---

# ▶️ Installation & Usage

## 1️⃣ Clone Repository

```bash
git clone https://github.com/your-username/FAKE-NEWS-PREDICTION.git
```

## 2️⃣ Navigate to Project

```bash
cd FAKE-NEWS-PREDICTION
```

## 3️⃣ Install Required Libraries

```bash
pip install -r requirements.txt
```

## 4️⃣ Run Jupyter Notebook

```bash
jupyter notebook
```

Open:

```bash
src/code.ipynb
```

---

# 📋 Workflow

```text
Raw Dataset
   ↓
Data Cleaning
   ↓
Text Preprocessing
   ↓
Feature Engineering
   ↓
TF-IDF Vectorization
   ↓
Train/Test Split
   ↓
Model Training
   ↓
Model Evaluation
   ↓
News Prediction
```

---

# 🚀 Future Improvements

- 🌐 Streamlit Web Application
- 🤖 BERT-Based News Classification
- ⚡ Real-Time News Detection
- ☁ Cloud Deployment
- 📱 Interactive User Interface

---

# 👨‍💻 Author

## Dilshan Nethmin Wijayarathne

💻 Data Science Undergraduate

🤖 AI & Machine Learning Enthusiast

📊 Data Analytics and Intelligent Systems Developer

🌐 Full Stack Developer

---

# ⭐ Support

If you found this project useful:

⭐ Star the repository

🍴 Fork the project

🛠️ Contribute to improvements

---

<div align="center">

## 📰 Fake News Classification using Machine Learning

### Detecting Fake News with NLP & Logistic Regression

🚀 Thanks for Visiting

</div>
