# deepSentiment

The repository contains an LSTM deep learning network trained for a 10 class sentiment classification.

Data: Training Data: train, test and val data sets from the stanford movie review data.
glove: Glove trained embeddings.

Train Code:utility_functions - Helper functions used for model training.
sentiment_rnn_train - Main LSTM Deep learning training code.

Model: The best model fromt the training is saved here as .hdf5 file. This contains the model weights.

Prediction Code: This is to deploy the model as an api micro service. 


Please see the blog for more details on the model: https://medium.com/@prajwalshreyas/sentiment-analysis-for-text-with-deep-learning-2f0a0c6472b5
