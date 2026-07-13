# 🍽️ Yelp Review Sentiment Analysis using Machine Learning & Deep Learning

An end-to-end Natural Language Processing (NLP) project that classifies Yelp restaurant reviews into positive and negative sentiment using both classical machine learning and deep learning models. This project compares multiple text representation techniques and neural network architectures to understand their effectiveness for sentiment classification.

---

## 📌 Project Overview

Customer reviews provide valuable insights into user satisfaction and business performance. The objective of this project is to automatically classify Yelp reviews as positive or negative using Natural Language Processing techniques.

The project evaluates traditional machine learning algorithms alongside deep learning and transformer-based models to compare their performance, scalability, and practical applications.

---

## 🎯 Objectives

- Build an end-to-end NLP pipeline for sentiment classification.
- Compare classical Machine Learning and Deep Learning approaches.
- Evaluate different text representation techniques.
- Analyze model performance using standard evaluation metrics.
- Identify the best-performing model for sentiment prediction.

---

## 📂 Dataset

**Source:** Yelp Open Dataset

The dataset contains customer reviews collected from Yelp.

### Data Characteristics

- Restaurant Reviews
- English Language
- Binary Sentiment Classification
- Text-based dataset

*(Add the exact number of reviews if available.)*

Example:

```
Positive Review
"The food was amazing and the service was excellent."

Negative Review
"The food was cold and the staff was rude."
```

---

## 🛠️ Technologies Used

### Programming

- Python

### Libraries

- Pandas
- NumPy
- Scikit-learn
- PyTorch
- TensorFlow
- HuggingFace Transformers
- NLTK
- Matplotlib
- Seaborn

---

## 🔄 Project Pipeline

```
Raw Yelp Reviews
        │
        ▼
Text Cleaning
        │
        ▼
Tokenization
        │
        ▼
Feature Engineering
        │
        ▼
Model Training
        │
        ▼
Model Evaluation
        │
        ▼
Performance Comparison
```

---

## 🤖 Models Evaluated

### Classical Machine Learning

- Logistic Regression
- Support Vector Machine (SVM)
- Naive Bayes
- Decision Tree
- Random Forest

### Deep Learning

- RNN
- LSTM
- GRU

### Transformer Models

- BERT
- Fine-tuned BERT
- LoRA Fine-tuning *(if applicable)*

---

## 📊 Evaluation Metrics

Models were evaluated using:

- Accuracy
- Precision
- Recall
- F1 Score
- ROC-AUC

---

## 📈 Results

| Model | Accuracy | Precision | Recall | F1 Score |
|--------|----------|-----------|--------|----------|
| Logistic Regression | XX | XX | XX | XX |
| SVM | XX | XX | XX | XX |
| Random Forest | XX | XX | XX | XX |
| LSTM | XX | XX | XX | XX |
| BERT | XX | XX | XX | XX |

*(Replace with your actual results.)*

---

## 📷 Sample Results

Include screenshots such as:

- Confusion Matrix
- ROC Curve
- Accuracy Comparison
- Training Curves

---

## 📁 Repository Structure

```
├── data/
├── notebooks/
├── models/
├── figures/
├── report/
├── requirements.txt
└── README.md
```

---

## 🚀 How to Run

Clone the repository

```bash
git clone https://github.com/Darsh-OO7/Yelp-Sentiment-Analysis.git
```

Install dependencies

```bash
pip install -r requirements.txt
```

Run the notebook

```bash
jupyter notebook
```

---

## 💡 Key Learnings

- Built complete NLP pipelines from preprocessing to deployment-ready models.
- Compared classical ML algorithms with deep learning architectures.
- Evaluated transformer-based models for sentiment classification.
- Understood trade-offs between accuracy, computational cost, and interpretability.
- Applied feature engineering and model evaluation techniques for text classification.

---

## 📌 Future Improvements

- Deploy the best-performing model using FastAPI.
- Integrate a Streamlit web application.
- Explore multilingual sentiment analysis.
- Experiment with larger transformer models.

---

## 👨‍💻 Author

**Darsh Shetty**

MS Data Science | Worcester Polytechnic Institute

LinkedIn:
https://linkedin.com/in/darsh-shetty-335354205

GitHub:
https://github.com/Darsh-OO7
