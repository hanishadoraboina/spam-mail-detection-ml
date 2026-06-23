
# 📧 Spam Mail Detection using Machine Learning

## 📌 Project Overview

Spam emails and messages have become a major challenge in digital communication. This project implements a Machine Learning-based Spam Mail Detection System that automatically classifies messages as **Spam** or **Ham (Legitimate Messages)**.

The model utilizes Natural Language Processing (NLP) techniques and a Multinomial Naive Bayes classifier to analyze message content and predict whether a message is spam.

---

## 🎯 Objectives

* Detect spam messages automatically.
* Preprocess and clean textual data.
* Convert text into machine-readable numerical features.
* Train a Machine Learning model for classification.
* Evaluate model performance using various metrics.

---

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Regular Expressions (Regex)
* Scikit-learn
* TF-IDF Vectorization
* Multinomial Naive Bayes
* Matplotlib
* Seaborn

---

## 📂 Dataset

The dataset contains text messages categorized into:

| Category | Description                                 |
| -------- | ------------------------------------------- |
| Ham      | Legitimate Messages                         |
| Spam     | Unwanted Promotional or Fraudulent Messages |

Example:

| Category | Message                                           |
| -------- | ------------------------------------------------- |
| Ham      | Hey, are we meeting today?                        |
| Spam     | Congratulations! You won a free prize. Click now! |

---

## ⚙️ Project Workflow

### 1. Data Collection

* Load the dataset using Pandas.
* Explore message categories and structure.

### 2. Data Preprocessing

* Remove unwanted characters.
* Convert text to lowercase.
* Remove punctuation and noise.
* Clean message content.

### 3. Feature Engineering

* Apply TF-IDF Vectorization.
* Transform textual messages into numerical vectors.

### 4. Model Training

* Split dataset into training and testing sets.
* Train a Multinomial Naive Bayes classifier.

### 5. Model Evaluation

Evaluate the model using:

* Accuracy Score
* Precision Score
* Recall Score
* Confusion Matrix
* Classification Report

### 6. Prediction

The trained model predicts whether a new message is:

* Spam
* Ham

---

## 🧠 Machine Learning Algorithm

### Multinomial Naive Bayes

Multinomial Naive Bayes is a probabilistic classification algorithm widely used for text classification tasks such as:

* Spam Detection
* Sentiment Analysis
* Document Categorization
* Email Filtering

Advantages:

✔ Fast Training
✔ High Efficiency
✔ Excellent Performance on Text Data
✔ Easy Implementation

---

## 📊 Evaluation Metrics

The model performance is analyzed using:

* Accuracy
* Precision
* Recall
* F1-Score
* Confusion Matrix

These metrics help determine how effectively the model identifies spam messages while minimizing false predictions.

---

## 🚀 How to Run

### Clone the Repository

```bash
git clone https://github.com/yourusername/spam-mail-detection.git
```

### Navigate to Project Folder

```bash
cd spam-mail-detection
```

### Install Required Libraries

```bash
pip install pandas numpy scikit-learn matplotlib seaborn
```

### Run the Notebook

```bash
jupyter notebook
```

Open:

```bash
spam_mail.ipynb
```

---

## 📈 Future Enhancements

* Deploy as a Web Application
* Real-Time Email Classification
* Deep Learning-based Spam Detection
* Integration with Email Services
* Advanced NLP Techniques

---

## 📚 Learning Outcomes

Through this project, I gained hands-on experience in:

* Machine Learning Fundamentals
* Natural Language Processing
* Text Preprocessing
* Feature Extraction using TF-IDF
* Classification Algorithms
* Model Evaluation Techniques

---

## 👩‍💻 Author

**Hanisha Doraboina**

B.Tech Artificial Intelligence (2023–2027)
Madanapalle Institute of Technology & Science (MITS)

Passionate about Artificial Intelligence, Machine Learning, NLP, and building real-world AI solutions.

---

⭐ If you found this project useful, consider giving it a star!
