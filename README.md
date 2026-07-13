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

The project uses review and business data from the Yelp Open Dataset.

For sentiment modeling, a balanced subset of **30,000 restaurant reviews** was created:

- **18,485 positive reviews**
- **11,515 negative reviews**
- **24,000 training samples**
- **6,000 testing samples**
- Binary sentiment classification
- Positive and negative review labels

### Data Characteristics

- Restaurant Reviews
- English Language
- Binary Sentiment Classification
- Text-based dataset


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

## 📈 Model Performance

The models were evaluated on a test set of 6,000 Yelp reviews using accuracy, precision, recall, and F1 score.

| Model | Accuracy | Precision | Recall | F1 Score |
|---|---:|---:|---:|---:|
| Logistic Regression (Graph-Based Features) | 89.78% | 92.06% | 87.00% | 89.46% |
| Support Vector Machine (Graph-Based Features) | 89.28% | 91.98% | 86.00% | 88.89% |
| Random Forest (Graph-Based Features) | 86.53% | 89.25% | 83.00% | 86.01% |
| LSTM | 83.18% | 89.09% | 80.33% | 84.48% |
| BERT without Fine-Tuning | 82.06% | 90.33% | 79.36% | 84.49% |
| Fine-Tuned BERT | 83.64% | 95.37% | 77.44% | 85.48% |
| BERT with LoRA | 88.32% | 90.91% | 90.23% | **90.57%** |

### Key Result

The graph-based Logistic Regression model achieved the highest accuracy at **89.78%**, while **BERT with LoRA achieved the strongest F1 score of 90.57%**, providing the best balance between precision and recall.

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
