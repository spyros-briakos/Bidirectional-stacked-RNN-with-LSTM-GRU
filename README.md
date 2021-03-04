# Bidirectional-stacked-RNN-with-LSTM-GRU
Our goal is to develop a sentiment classifier using a bidirectional stacked RNN with LSTM/GRU cells for twitter sentiment analysis.


432423432
For
the development of the models, you can experiment with the number of stacked RNNs,
the number of hidden layers, type of cells, skip connections, gradient clipping and dropout
probability. Document the performance of different configurations on your final report.
Use the Adam optimizer and the binary cross-entropy loss function. Remember to transform the predicted logits to probabilities using a sigmoid function. You should also utilize
pre-trained word embeddings (GloVe) as the initial embeddings to input on your models.
For the best model you found:
• Compute precision, recall and F1 for each class.
• Plot the loss vs. epochs curve and the ROC curve and explain what you see.
• Compare with your best model from Homework 2.
Your solution should be implemented in PyTorch and we expect your report to be well
documented.
