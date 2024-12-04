# Poetry Generating Text Model

This project aims to create a text model that can predict the next word in a given text sequence. The model will be trained using a corpus of Shakespeare's sonnets, and some helper functions will be provided to preprocess the data.

## Overview

The goal of this project is to implement a text generator model that can predict the next word in a given sequence of words. The model will be trained using the [Shakespeare Sonnets Dataset](https://www.opensourceshakespeare.org/views/sonnets/sonnet_view.php?range=viewrange&sonnetrange1=1&sonnetrange2=154), which contains more than 2000 lines of text extracted from Shakespeare's sonnets.

## Model Architecture

The text generator model is implemented as follows:

The model architecture consists of three layers:
1. An Embedding layer with input size equal to the `total_words` vocabulary size and output dimension 100.
2. A Bidirectional LSTM layer with 100 units, which helps capture context from both directions in the input sequence.
3. A Dense layer with a size equal to `total_words` and a softmax activation function, used for predicting the next word from the vocabulary.


## Acknowledgments

This project is part of the Lab Assignment from the course "Deep Learning" for my Masters in Data Science from IIT Jammu. 





