
# 💊 Drug Recommendation through Patient Review Classification using ML and NLP

A healthcare-focused project that uses **Natural Language Processing** and **Machine Learning** to classify patient medical conditions from drug reviews and recommend appropriate medications.  


## 📌 Overview

This system reads and classifies patient drug reviews, identifies medical conditions, and recommends top-rated drugs.  
It applies vectorization techniques like **TF-IDF**, **BoW**, and **BERT** to process real-world textual data.  
Among several models tested, the **Passive Aggressive Classifier** achieved the best performance with **96% accuracy** using trigram features.


## 🧠 Key Features

- Classifies health conditions from patient reviews (e.g., Diabetes, Depression, Birth Control)
- Recommends suitable drugs based on user experience
- Utilizes both conventional ML models and advanced NLP embeddings
- Enhances patient-centered care with real-world data analysis


## 🗂️ Dataset

- Source: **UCI Machine Learning Repository**
- Fields include: Drug Name, Condition, Review Text, Rating, and Timestamp
- Unstructured and highly varied text—ideal for NLP tasks


## 🧪 Methodology

1. **Data Preprocessing**:
   - Cleaning (removing stopwords, punctuation, HTML)
   - Tokenization and Lemmatization

2. **Feature Engineering**:
   - Vectorization: TF-IDF, BoW
   - Embeddings: Word2Vec, BERT

3. **Model Training**:
   - Algorithms: Passive Aggressive Classifier, Naive Bayes
   - Accuracy: **PAC with trigrams = 96%**
   - BERT fine-tuned for improved contextual classification


## 📊 Confusion Matrix

A confusion matrix was generated to evaluate the accuracy of the Passive Aggressive Classifier across various disease classes.


## 🚀 Future Work

- Explore text augmentation (e.g., back-translation)
- Improve balance across medical condition classes
- Expand to multilingual and region-specific medical reviews
- Deploy via a full-stack app or cloud API


## 🧾 Conclusion

This project shows how unstructured patient feedback can power meaningful healthcare insights. The system automates condition classification and enhances drug recommendations, reducing cognitive load for healthcare providers and aiding patients in making informed choices.
