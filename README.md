# 📚 NLP Representation Learning & Book Clustering

[![Python](https://img.shields.io/badge/Python-3.10%2B-3776AB?style=flat-square&logo=python)](https://www.python.org/)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626?style=flat-square&logo=jupyter)](https://jupyter.org/)
[![Hugging Face](https://img.shields.io/badge/Models-BERT%20%7C%20Transformers-FFD21E?style=flat-square)](https://huggingface.co/)
[![Scikit-Learn](https://img.shields.io/badge/ML-Scikit--Learn-F7931E?style=flat-square&logo=scikit-learn)](https://scikit-learn.org/)

Exploratory Natural Language Processing (NLP) notebooks and experiments covering dense representation learning, contextual embeddings with BERT, dense word vectors (Word2Vec / GloVe), and unsupervised clustering across Goodreads book datasets.

---

## 🔬 Research & Notebook Modules

### 1. Contextual Transformers (`bert-notbook.ipynb`)
- Contextual embedding generation using pre-trained Transformer architectures (`BERT`).
- Tokenization pipelines, attention mechanisms, and hidden state feature extraction for downstream semantic analysis.

### 2. Dense Word Embeddings (`word_embedding.ipynb`)
- Training and evaluation of static dense word embeddings (Word2Vec Skip-Gram / CBOW, GloVe).
- Semantic similarity evaluations, vector arithmetic (analogies), and cosine distance visualizations.

### 3. Clustering & Genre Classification (`book_genre_classification_and_clustering.ipynb`)
- Dimensionality reduction and unsupervised clustering (K-Means, Agglomerative) on book description embeddings.
- Genre classification pipelines predicting category labels from latent text features.
- Evaluated on curated book subsets (`top_3000_rated_books.csv` and `books_with_description_emb.csv`).

---

## 📂 Repository Contents

```text
├── bert-notbook.ipynb                             # Transformer & BERT representation pipelines
├── word_embedding.ipynb                           # Word2Vec and dense embedding experiments
├── book_genre_classification_and_clustering.ipynb # Genre classification and semantic clustering
├── top_3000_rated_books.csv                       # Curated Goodreads book dataset
└── books_with_description_emb.csv                 # Pre-computed dense embedding vectors
```

---

## ⚡ Environment & Setup

```bash
# Clone the repository
git clone https://github.com/Hosein1011/nlp-embeddings-clustering.git
cd nlp-embeddings-clustering

# Create virtual environment
python -m venv venv
source venv/bin/activate  # On Windows: .\venv\Scripts\activate

# Install required packages
pip install torch transformers scikit-learn pandas numpy jupyter
jupyter notebook
```
