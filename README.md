📌 Project Summary
This project demonstrates the use of Word2Vec from the Gensim library to learn word relationships from a text paragraph. It includes:

Text Preprocessing: Cleaning the input text using NLTK (removing stopwords, punctuation, and converting to lowercase).

Tokenization: Splitting the paragraph into sentences and words.

Model Training: Training a Word2Vec model using the cleaned and tokenized text.

Word Analysis:

Generating vector representations for words (e.g., model.wv['war'])

Finding similar words using cosine similarity (e.g., model.wv.most_similar('freedom'))

🔍 This is a small-scale demo for learning purposes. Word2Vec models typically require large datasets to produce meaningful results.

