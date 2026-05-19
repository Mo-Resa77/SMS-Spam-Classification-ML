# SMS Spam Classification Engine (Dual-Dataset NLP Framework)

An advanced Natural Language Processing (NLP) and Text Classification engine built to detect fraudulent and spam SMS messages using Supervised Machine Learning models across multiple independent datasets.

## 📊 Core Architecture & Engineering Features
- **Dual-Dataset Benchmarking:** Rigorous model evaluation conducted across two distinct secure SMS corpora (SSCD1 & SSCD2) to audit generalization and combat overfitting.
- **NLP Text Preprocessing Pipeline:** Complete textual sanitization including advanced regular expression filtering (Regex cleaning), tokenization, and WordNet Lemmatization via NLTK.
- **Feature Engineering:** Implemented Bag-of-Words text representation utilizing `CountVectorizer` paired with `TfidfTransformer` to compute optimal term frequency-inverse document frequency weighting matrices.
- **Model Comparison:** Cross-benchmarked **Multinomial Naive Bayes (NB)** against **Logistic Regression (LR)** to determine the most stable decision boundaries for high-dimensional text fields.

## 🛠️ Technology Stack
- **Languages:** Python
- **Libraries:** Pandas, NLTK, Scikit-Learn
- **Environment:** Google Colab / Jupyter Notebook

## 🔬 Performance & Results Strategy
The pipeline applies text tokenization strategies to capture spam signatures and structural semantic anomalies, sorting the final model rankings dynamically by validation accuracy score to output production-ready classification baselines.
