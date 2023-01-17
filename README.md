# IMDB Dataset Keras sentimental classification using LSTM
This is simple Neural Network which was built with LSTM in Keras for sentimental classification on IMDB dataset.
**Sentiment Analysis** is a classification of emotions (in this case, positive and negative) on text data using text analysis techniques (In this case LSTM).
Long short-term memory (LSTM) is an artificial neural network used in the fields of artificial intelligence and deep learning. Unlike standard feedforward neural networks, LSTM has feedback connections. Such a recurrent neural network (RNN) can process not only single data points (such as images), but also entire sequences of data (such as speech or video). This characteristic makes LSTM networks ideal for processing and predicting data.
**Keras** is a high-level, deep learning API developed by Google for implementing neural networks. It is written in Python and is used to make the implementation of neural networks easy. It also supports multiple backend neural network computation.

### Dataset
<hr>
In this work I use IMDB dataset from keras.datasets.
This is a dataset of 25,000 movies reviews from IMDB, labeled by sentiment (positive/negative). Reviews have been preprocessed, and each review is encoded as a list of word indexes (integers). For convenience, words are indexed by overall frequency in the dataset, so that for instance the integer "3" encodes the 3rd most frequent word in the data. This allows for quick filtering operations such as: "only consider the top 10,000 most common words, but eliminate the top 20 most common words".

### Architecture
<hr>
<ol type="1">
    <li>Embedding Layer</li>
    <li>Convolutional 1D Layer</li>
    <li>MaxPooling1D Layer</li>
    <li>LSTM Layer</li>
    <li>Dense (activation function using Sigmoid)</li>
    <li>Optimizer: Adam, Loss Function: Binary Crossentropy</li>
</ol>

### References
<hr>
<li><a href="https://keras.io/">
    https://keras.io/</a>
</li>
<li><a href="https://keras.io/api/datasets/imdb/">
    https://keras.io/api/datasets/imdb/</a>
</li>

<img src="https://www.michaelfxu.com/assets/images/posts/lstm_diagram.png" />
<li><a href="https://www.kaggle.com/ngyptr/lstm-sentiment-analysis-keras">
    https://www.kaggle.com/ngyptr/lstm-sentiment-analysis-keras</a>
</li>
<li><a href="https://towardsdatascience.com/lstm-networks-a-detailed-explanation-8fae6aefc7f9">
    https://towardsdatascience.com/lstm-networks-a-detailed-explanation-8fae6aefc7f9</a>
</li>

