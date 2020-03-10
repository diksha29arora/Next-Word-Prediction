# Next Word Prediction
Its is a Natural Language Processing based project which is capable of predicting the following word based on the previous words of a sentence.

In this project, the dataset has been taken from a text file "moby.txt", of the size 1.3 MB. After preprocessing, it contains around 1.23 Million words. The dataset is prepared from a raw corpus of text in a way that first 25 words are taken as features and the 26th or the next word as label. Then, a function called "tokenize" from keras is used to encode the text into word embeddings. The model is then trained on Google Colab for faster training by uploading the moby.txt file on colab using 'files.upload()' command in the code.

The model is trained on basic LSTM based neural network with 256 batch size and run the model for 350 epochs. The model and the text is then saved using "pickle".
