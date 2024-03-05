# Greek Elections 2019 Tweet Classifier
This repository contains three models developed for classifying tweets related to the 2019 Greek elections into three classes: Positive, Negative, or Neutral. 
The models were primarily constructed utilizing sklearn, PyTorch, and the hyperparameter optimization framework Optuna.
Each notebook within the project repository contains various text preprocessing methods, including capitalization, accent removal, stemming, lemmatization, and more.

# Notebooks
- Logistic-Regression-Model.ipynb: This notebook details the development of a Logistic Regression classifier using primarily the sklearn library.

- Feed-Forward-Neural-Network.ipynb: This notebook outlines the construction of a Softmax classifier utilizing the PyTorch framework.

- Recurrent-Neural-Network.ipynb: This notebook delves into the development of a Softmax classifier with two fundamental components. The first component is a Recurrent Neural Network responsible for generating a representation of the corresponding tweet using bidirectional LSTM or GRU cells. The second component is a Softmax classifier, which classifies the tweet based on the representation obtained from the recurrent neural network.
