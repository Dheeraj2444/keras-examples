# Keras Examples

Keras is a user friendly high-level deep learning framework that uses Theano as well as TensorFlow as a backend and helps you easily build complex deep learning architectures. Here, I'll share how we can train different deep learning architectures using Keras.

**Note**: Before using Keras, it is advisable to understand detailed working of all these frameworks and implement them using pure numpy at first for better understanding (at least feed forward neural network, including backpropagation).<br><br>

* **Binary Classification**
	* [feed_forward_neural_network.ipynb](https://github.com/Dheeraj2444/keras-examples/blob/master/feed_forward_neural_network.ipynb): Trained a **Multi-Layered Perceptron (MLP)** for binary classification using [Ionosphere Data Set](https://archive.ics.uci.edu/ml/datasets/ionosphere)<br>
* **MNIST Digits Classification**
	* [convolutional_nerual_network.ipynb](https://github.com/Dheeraj2444/keras-examples/blob/master/convolutional_nerual_network.ipynb): Trained a **Convolutional Neural Network (CNN)** to classify MNIST digits<br>
* **Part-of-Speech Tagging**
	* [pos_tagging.ipynb](https://github.com/Dheeraj2444/keras-examples/blob/master/pos_tagging.ipynb): Trained a **3-layered neural network** on Penn treebank corpus to predict the part of speech tag of a word in a sentence
* **Sequence Classification**
	* [sentence_level_classification_cnn.ipynb](https://github.com/Dheeraj2444/keras-examples/blob/master/sentence_level_classification_cnn.ipynb): Trained a **1-D Convolutional Neural Network** to classify a given question sentence into one of the six possible categories
	* [sentence_classification_rnn.ipynb](https://github.com/Dheeraj2444/keras-examples/blob/master/sentence_classification_rnn.ipynb): Trained a **Stacked bi-directional LSTM** network to classify a given question sentence into one of the possible six categories
* **Sentiment Analysis**
	* [sentiment_analysis_LSTM.ipynb](https://github.com/Dheeraj2444/keras-examples/blob/master/sentiment_analysis_LSTM.ipynb): Trained a **Long Short Term Memory (LSTM)** model to perform sentiment analysis over IMDB movie reviews<br>
* **Dialogue-Act Recognition**
	* [dialogue_act_recognition.ipynb](https://github.com/Dheeraj2444/keras-examples/blob/master/dialogue_act_recognition.ipynb): Trained a 3-layered neural network on the [NPS Chat](http://faculty.nps.edu/cmartell/NPSChat.htm) corpus to recognize an act from a given dialogue