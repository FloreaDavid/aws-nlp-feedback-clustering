# 📝 Review Topic Modeling with BERTopic on AWS

This project explores **topic modeling of user reviews** using **BERTopic** with sentence embeddings, CountVectorizer, and NLP preprocessing.  
The implementation runs on **AWS SageMaker**, storing datasets and models in **Amazon S3** for scalable training and deployment.

## ✨ Features
- **Dataset:** Yelp Reviews (`yelp_review_full`)
- **Preprocessing:** SpaCy lemmatization, stopword & punctuation removal
- **Vectorization:** CountVectorizer with n-grams
- **Embeddings:** SentenceTransformers (`all-mpnet-base-v2`)
- **Topic Modeling:** BERTopic with automatic topic discovery
- **Deployment:** Model artifacts saved locally and uploaded to **Amazon S3**


## 🔧 Tech Stack
- **AWS SageMaker** + **S3**
- **Python**, **Pandas**
- **SpaCy** for NLP preprocessing
- **SentenceTransformers** for embeddings
- **Scikit-learn** (normalization, vectorization)
- **BERTopic** for topic modeling & visualization
