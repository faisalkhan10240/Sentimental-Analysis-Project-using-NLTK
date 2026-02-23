📌 Sentiment Analysis: Lexicon vs Transformer Comparison
📖 Overview
This project compares two different approaches for sentiment analysis:
VADER (Lexicon-Based Model)
RoBERTa (Transformer-Based Model)
The objective was to evaluate how a traditional rule-based model performs against a modern deep learning model on real customer review data.
🎯 Problem Statement
Customer reviews contain valuable insights about product perception.
The goal of this project is to analyze review sentiments and compare the performance of:
A rule-based lexicon approach
A pretrained transformer model
🗂 Dataset
Amazon product reviews dataset
Star ratings (1–5) used as reference sentiment labels
⚙️ Methodology
Data loading and basic preprocessing
Sentiment scoring using:
VADER polarity scores
RoBERTa pretrained sentiment model
Comparative analysis of:
Positive
Neutral
Negative scores
Visualization using seaborn and matplotlib
📊 Key Observations
Transformer-based RoBERTa captures contextual sentiment more effectively.
VADER performs reasonably well on straightforward positive/negative text.
Disagreement observed in sarcastic or complex statements.
Deep learning models show better semantic sensitivity.
🛠 Tech Stack
Python
Pandas
Matplotlib
Seaborn
NLTK (VADER)
HuggingFace Transformers
PyTorch