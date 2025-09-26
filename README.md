# Sentiment_Analysis_with_LSTM-
This project performs sentiment analysis on the Kaggle “Twitter US Airline Sentiment” dataset using PyTorch. It includes a baseline LSTM and an improved BiGRU with pre-trained GloVe embeddings, along with data cleaning, tokenization, batching, training, and evaluation (accuracy, precision/recall/F1, confusion matrix).
Sentiment Analysis with LSTM (PyTorch) on Twitter Airline Tweets

This project performs sentiment analysis on the Kaggle “Twitter US Airline Sentiment” dataset using PyTorch.
It includes a baseline LSTM and an improved BiGRU with pre-trained GloVe embeddings, along with data cleaning, tokenization, batching, training, and evaluation (accuracy, precision/recall/F1, confusion matrix).

Highlights

Models: Baseline LSTM; Improved BiGRU + GloVe (300d)

Training setup: epochs=10, batch_size=64

Libraries: PyTorch, NumPy, pandas, scikit-learn, NLTK, spaCy, wordcloud, matplotlib/seaborn, tiktoken, torchinfo

Results (from notebook):

Metric	LSTM (Base)	BiGRU + GloVe	Δ
Accuracy	0.7678	0.8101	+0.0423
Loss	1.2309	0.5148	−0.7161
Precision (macro)	0.6966	0.7765	+0.0799
Recall (macro)	0.7387	0.7620	+0.0234
F1 (macro)	0.7129	0.7626	+0.0497

Confusion matrices show clearer class boundaries with the BiGRU model, especially for the neutral class.
