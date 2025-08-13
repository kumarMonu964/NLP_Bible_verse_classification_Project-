# NLP_Bible_verse_classification_Project-
Performed text classification (Multi-Class classification) using fundamentals of NLP, build and trained a lot of models right from BOW, TF-TDF to Doc2Vec, experimented with a lot of vector embedding techniques and classification models to find the best model to classify bible verses.


This NLP project classifies Bible verses into thematic categories using classical and modern text representation techniques. It includes exploratory data analysis, advanced feature engineering, iterative model evaluations, and final deployment using FastAPI (not yet deployed)

---

## 📌 Objective

Build a multi-class classification model that classifies Bible verses into their respective thematic categories (Bible Books) using NLP techniques and different embedding strategies.

---

## 🧠 Project Workflow

### 🔹 Phase 1: Data Handling
- Data acquisition from publicly available Bible text corpora
- Data cleaning: removal of noise, punctuation, special characters

### 🔹 Phase 2: Exploratory Data Analysis
- Class distribution
- Verse length analysis
- Word frequency and word clouds

### 🔹 Phase 3: Preprocessing
- Tokenization
- Stopword removal
- Lemmatization
- Handling class imbalance 

### 🔹 Phase 4: Feature Engineering
- Bag of Words (BoW)
- TF-IDF (Unigrams & Bigrams)
- Word2Vec (using Gensim)
- Doc2Vec
- BERT embeddings (for deep contextual understanding)

### 🔹 Phase 5: Modeling & Evaluation
Each embedding technique was combined with different models:
- Logistic Regression
- Naive Bayes
- Random Forest
- Support Vector Machine (SVM)
- Deep Learning (Optional)
  
Each combination was evaluated using:
- Accuracy, Precision, Recall, F1-score
- Confusion matrix

### 🔹 Phase 6: Deployment (Coming Soon)
- The best-performing model will be deployed using **FastAPI**
- Hosted on **GitHub Pages or Render**

---

## 📊 Visual Results

📸 Sample Plots:

- all plots imcluded in the images folder
---

## 🛠️ Tools & Libraries Used

- Python, NumPy, Pandas
- NLTK (tokenization, stopwords, lemmatization)
- Gensim (Word2Vec, Doc2Vec)
- Scikit-learn (ML models and evaluation)
- Matplotlib, Seaborn, WordCloud
- TQDM (preprocessing progress bars)


---

## 🚀 How to Run

1. Clone the repo:
   ```bash
   git clone https://github.com/yourusername/Bible-Verse-Classification.git
   cd Bible-Verse-Classification

