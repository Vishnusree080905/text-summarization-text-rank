# text-summarization-text-rank
AICTE INTERNSHIP PROJECT
# Text Summarization Using TextRank Algorithm

## 📌 Project Overview
This project is built as part of the AICTE Virtual Internship. It demonstrates how to summarize long news articles using the **TextRank** algorithm, an unsupervised extractive summarization method based on PageRank.

## 🔍 What It Does
- Loads a real-world news dataset (`cnn_dailymail`)
- Processes and tokenizes the text into sentences
- Applies the TextRank algorithm to score and rank sentences
- Produces a concise summary from the top-ranked sentences

## 📂 Technologies Used
- Python
- Jupyter Notebook
- NLTK
- HuggingFace Datasets
- Gensim (optional)

## 📈 Dataset
The project uses the `cnn_dailymail` dataset (via HuggingFace), which contains news articles and summaries.

## 🚀 How to Run
1. Clone this repo or download the notebook.
2. Install dependencies:
   ```bash
   pip install nltk gensim transformers datasets jupyter
