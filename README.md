# Next-Word-Prediction
Our problem statement is to predict the next word of a sentence given its previous words and a corpus for training the model. We have trained neural models and n-gram language models to predict the next word of a sequence.

LSTM Model
FileName: NextWordPrediction_LSTM_optimized-GPU.ipynb

This code needs to be run on Google Collab(25 GB RAM) due to large memory requirements, unless you have a big RAM.
Google Collab - Set the runtime to GPU. Since it uses GPU based libraries.

The files that need to be accessed are on my personal google drive folder.
You need to mount your drive from the notebook(code in the notebook) and add the required files to your personal drive which are as follows.

1.emailTokens
https://drive.google.com/open?id=1AE1Rx2EwWWSu3kpr-nMX1ANnzq8zs2iC

2.vocab.txt
https://drive.google.com/open?id=13fKFol5ARV0yPniQyX8e06Fopq8H3_sy

Add these files to a folder Named: "Next Word Prediction" in your personal drive.

You can then access it from the code using the path 'drive/My Drive/Next Word Prediction/filename'.(Code in notebook)

You can run the code sequentially cell by cell in the notebook.


Feature Engineering Code:

FileName: NextWordPrediction-FeatureEngineering.ipynb

Get the emails dataset from Kaggle.(1GB file)
https://www.kaggle.com/wcukierski/enron-email-dataset

Add it in the path ./emailData/emails.csv with respect to the feature engineering notebook.

Download Google News Vectors, unzip it and place it in the same directory as the current notebook.
https://github.com/mmihaltz/word2vec-GoogleNews-vectors

And then run the notebook cell by cell.


N-gram Model with Laplace smoothing
FileName: Word_Prediction_Laplace.ipynb

Run the code from the block "For testing the model"
For this you need to download all the files from the following folder.

https://drive.google.com/open?id=1w6atfLocHpEAKguwMzirgU8rPSqinLdt














