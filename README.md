# Bidirectional-stacked-RNN-with-LSTM-GRU
Our goal is to develop a sentiment classifier using a bidirectional stacked RNN with LSTM/GRU cells for twitter sentiment analysis, from this [dataset](https://drive.google.com/file/d/1dTIWNpjlrnTQBIQtaGOh0jCRYZiAQO79/view), which was cleaned in this [notebook](https://github.com/spympr/Bidirectional-stacked-RNN-with-LSTM-GRU/blob/main/PreProcessing.ipynb).

We implemented a class, called LSTM_GRU, where with help of her we managed to experiment with:
* Number of stacked RNNs
* Number of hidden layers
* Type of cells
* Gradient clipping
* Dropout probability

During our experimental procedure, we utilize the ***Adam optimizer*** and the ***Binary Cross-Entropy (BCE)*** loss function. 
Each experiment, which took place, was evaluated from ***learning curves***, ***classification report*** (which includes precision, recall and F1 score for each class) and ***ROC Curve's plot***.
In this last checkpoint of this [notebook](https://github.com/spympr/Bidirectional-stacked-RNN-with-LSTM-GRU/blob/main/LSTM_GRU_Classifier.ipynb), we decided to keep LSTM model, which aimed to have a pretty descent performance!

Note that notebook is well reported and was implemented with ***Machine Learning Library Pytorch***. Running's procedure took place on ***Google Colab***, enhanced with ***Cuda GPU!***
