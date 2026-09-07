# 🎬 AI-Based Movie Review Sentiment Analysis

An AI-based sentiment analysis project that classifies movie reviews into **Positive, Negative, or Neutral** categories using **NLP, Word2Vec, Sentence Transformers, Machine Learning, and Neural Networks**.

## 📌 Project Overview

The project explores different text embedding techniques and compares their performance with Machine Learning and Deep Learning models.

### 🔄 Project Workflow

**Movie Reviews → Text Embeddings → ML/DL Models → Sentiment Prediction → Model Comparison**

## 🧠 Embedding Techniques

Two approaches are used to convert text into numerical representations:

* **Word2Vec** – Generates word-level embeddings based on word context.
* **Sentence Transformer** – Generates sentence-level embeddings that capture semantic meaning.

## 🤖 Models Used

The embeddings are combined with different models:

| Embedding            | Model          |
| -------------------- | -------------- |
| Word2Vec             | Random Forest  |
| Sentence Transformer | Random Forest  |
| Word2Vec             | Neural Network |
| Sentence Transformer | Neural Network |

## 📊 Model Comparison

The models are evaluated using **training and testing accuracy** to understand their learning ability and generalization performance.

* **Word2Vec + Random Forest:** Shows underfitting with low training and testing accuracy.
* **Sentence Transformer + Random Forest:** Improves performance and generalization compared to Word2Vec-RF.
* **Word2Vec + Neural Network:** Improves accuracy and reduces underfitting, but Word2Vec has limited contextual understanding.
* **Sentence Transformer + Neural Network:** Provides advanced contextual representations but may show overfitting when model complexity is high relative to the available data.

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Gensim / Word2Vec
* Sentence Transformers
* Neural Networks
* Natural Language Processing (NLP)

## 🎯 Objective

The main objective is to **compare different combinations of text embeddings and ML/DL models** and identify an effective approach for movie review sentiment analysis.

## 🚀 Key Learning Outcomes

* Text preprocessing and NLP
* Word embeddings using Word2Vec
* Sentence-level embeddings using Sentence Transformers
* Machine Learning model development
* Neural Network model development
* Model evaluation and comparison
* Understanding underfitting and overfitting
