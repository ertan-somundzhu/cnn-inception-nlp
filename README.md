# cnn-inception-nlp
Combining CNNs and Inception blocks for sentiment classification

Here I tried to create a custom neural network architecture that combines regular convolutional neural networks with Inception blocks introduced in GoogLeNet[^fn1] for the purporse of sentiment analysis.<br><br>I tested the model on the IMDb Movie Reviews dataset.<br><br>Here the results:<br>Train accuracy: 0.93 (10th epoch)<br>Validation accuracy: 0.83 (10th epoch)<br>Test accuracy: 0.8 (almost)<br><br>Libraries used: Tensorflow (Keras)



[^fn1]: (https://arxiv.org/abs/1409.4842v1)
