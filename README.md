# RNN-LSTM-classification
Using recurrent neural network to classify SMS messages as spam or legitimate. The following shows my contribution to a course project titled " RNN LSTM classification"

# Introduction
We try to classify SMS messages as SPAM or HAM using LSTM algorithms. The notebook consists steps to process and explore the dataset, convert messages to vectors and applying DL techniques for the same.
The notebook uses a Recurrent Neural Network (RNN) and LSTM to classify the messages. RNNs are networks with loops in them, allowing information from previous time step to persist capable of handling long-term dependencies.

# Libraries required:

Pandas,Numpy,Sklearn,Matplotlib,Seaborn,Tensorflow, Keras

# Methadalogy

Data preprocessing - We have found that 4825 data has ham and only 747 spam.

![download](https://user-images.githubusercontent.com/99074712/154860314-18eefeb9-eb3e-43f1-88bd-4242f92a3cfd.png)

Label the target data with label encoder.

# Splitting Training and Testing datsets
Next, we splitted the dataset into training and testing set by having 20 percent of the data being testing and 80 percent being training.

# Tokenization
Tokenize the data and convert the text to sequences.
Words are called tokens and splitting of the words are called tokenization.

Add padding to ensure that all the sequences have the same shape.
There are many ways of taking the max_len and here an arbitrary length of 200 is chosen.

# Defining the model
With tesnorflow 2.0 defned the RNN model and used 'relu' activation for hidden layer and 'sigmoid' for output layer.
'Adam' optimizer used for compiling with binary loss function

# Result
With Accuracy metrics got model accuracy 1 in last epochs and validation accuracy around 98%.
![download](https://user-images.githubusercontent.com/99074712/154861020-e5fd9daf-7a6f-445c-bf5f-f3e1ad34a27b.png)


Test accuracy of the model was 98%

# Testing data
In last i made 2 different sentence by self to check working of my model and model performed very well in classifing ham and spam.
