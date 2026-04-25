# 📧 Email Spam Detection using TinyBERT

## 📌 Project Description
This project focuses on building a machine learning system for **spam email detection** using **Natural Language Processing (NLP)** techniques.  
A pre-trained transformer model, **TinyBERT**, is fine-tuned to classify emails as either **spam** or **not spam** based on their textual content.

The goal is to create an efficient and lightweight model that maintains high performance while being suitable for real-world applications.

---

## 🚀 Objectives
- Build a robust email spam classification system.
- Apply NLP preprocessing techniques to clean and prepare text data.
- Fine-tune a **TinyBERT** model for binary classification.
- Optimize model performance using evaluation metrics.

---

## 🧠 Approach

### 1. Data Preprocessing
- Cleaning email text (removing URLs, special characters, punctuation)
- Tokenization using TinyBERT tokenizer
- Padding and truncation for fixed-length inputs

### 2. Model Architecture
- Pre-trained model: **TinyBERT**
- Added classification head for binary output:
  - Spam
  - Not Spam

### 3. Training Process
- Loss Function: Cross-Entropy Loss
- Optimizer: AdamW
- Fine-tuning on labeled email dataset

### 4. Evaluation
- Accuracy
- Precision
- Recall
- F1-score

---

## 📊 Results
- High classification accuracy achieved after fine-tuning
- Efficient lightweight model suitable for deployment
- Good generalization on unseen email samples

---

## 🛠️ Technologies Used
- Python 🐍
- PyTorch / TensorFlow
- Hugging Face Transformers 🤗
- TinyBERT
- NLP techniques

