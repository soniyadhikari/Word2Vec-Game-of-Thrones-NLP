# Word2Vec on Game of Thrones Books

## 📌 Project Overview

This project implements the Word2Vec word embedding technique using the five books from the Game of Thrones series.

The objective is to understand how words are represented as numerical vectors and how a machine learning model learns semantic relationships between words based on their context.

## 📚 Dataset

- **Source:** [Game of Thrones Books – Kaggle](https://www.kaggle.com/datasets/khulasasndh/game-of-thrones-books)
- **Format:** TXT files
- **Number of books:** 5

The dataset is downloaded directly using the Kaggle API.

## 🛠️ Technologies Used

- Python
- Google Colab
- Gensim
- NLTK
- NumPy
- Pandas
- Scikit-learn
- Plotly

## ⚙️ Project Workflow

1. Download the dataset using the Kaggle API.
2. Extract and load the five text files.
3. Perform sentence tokenization using NLTK.
4. Preprocess text using Gensim.
5. Train a Word2Vec model.
6. Explore word embeddings and semantic relationships.
7. Find similar words using the trained model.
8. Calculate similarity between selected words.
9. Visualize word embeddings using PCA in 3D.

## 🧠 Word2Vec Model

Word2Vec learns distributed representations of words by using their surrounding context.

The project explores:
- Word vector representations.
- Context-based learning.
- Similarity between words.
- Semantic relationships between characters and concepts.

## 🔍 Experiments

Some experiments performed in this project include:

- Finding words similar to Daenerys.
- Exploring relationships between Arya and Sansa.
- Calculating similarity between Tywin and Sansa.
- Visualizing word embeddings in three dimensions.

## 🚀 How to Run

1. Clone this repository:

   ```bash
   git clone https://github.com/YOUR-USERNAME/Word2Vec-Game-of-Thrones.git
   ```

2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Open `notebooks/Word2Vec_GOT.ipynb` in Google Colab or Jupyter Notebook.

4. Configure your Kaggle API credentials.

5. Run the notebook cells sequentially.


## 👩‍💻 Author

**Soniya Adhikari**

Computer Engineering Student

## 📌 Future Improvements

- Compare CBOW and Skip-gram architectures.
- Experiment with different embedding dimensions.
- Tune Word2Vec hyperparameters.
- Explore additional word relationships.
- Improve word embedding visualizations.

## 📄 License

This repository contains implementation code. Refer to the original dataset source for its usage and licensing terms.
