
# 📧 Spam Email Classifier using Naïve Bayes

This project is a simple yet effective **email classification system** that predicts whether a given email is **Spam** or **Not Spam**.  
It uses the **Naïve Bayes algorithm** along with **CountVectorizer** from the scikit-learn library to convert email text into numerical features.

---

## 🧠 Overview

Email spam filtering is one of the most common applications of Natural Language Processing (NLP).  
In this project, the model is trained on sample email data to learn the probability of certain words appearing in spam vs non-spam emails.  
Once trained, it can classify new emails automatically.

---

## ⚙️ Technologies Used

- 🐍 **Python 3.x**  
- 📚 **scikit-learn** – for model building (Naïve Bayes, CountVectorizer,Pipeline)  
- 🧮 **NumPy** – for numerical operations  
- 📊 **Pandas** – for data handling  
- 🧠 **Google Colab / Jupyter Notebook** – for model development and training  

---

## 🧩 Algorithm Used: Naïve Bayes

The **Naïve Bayes algorithm** is a probabilistic classifier based on Bayes' Theorem.  
It assumes that all features (words) are independent of each other, which makes it simple yet powerful for text classification.

Mathematically, it calculates the probability of each class (Spam / Not Spam) given the words in the email and chooses the class with the highest probability.

---

## 🔡 Text Preprocessing

Before training, raw email text is converted into numerical form using **CountVectorizer**, which:
- Tokenizes (splits) each sentence into words  
- Builds a vocabulary of unique words  
- Converts each email into a vector of word frequencies  

---

## 🧾 Dataset

The model is trained on a small custom dataset containing labeled email samples — both spam and not spam.  
Dataset is given in this repo.

---

## 🚀 How to Run the Project

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/spam-email-classifier.git
   cd spam-email-classifier
