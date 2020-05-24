# text-generation-using-rnn
Recurrent Neural Network is class of artificial neural network. The most important thing using rnn are they have a memory. They can process the data and store what is required from the data processed and can be used for other data as well. There are two types of rnn maily they are Long Short-Term Memory (LSTM) and Gated Recurrent Unit (GRU).

In this repository we see how these Recurrent Neural Network is used on application for text generation. In our application we are using Character Level Implementation which is predicting character by character.

We can use different datasets, unlike mine we can use nietzsche.txt or shakespearse.txt or you can find many dataset online.

First we need to process the data as Input and Target data. This helps the algorithm learn what's the most probabilistic character to predict by our algorithm.

Use can use either of LSTM or GRU.

Then comes training part where you train using your dataset which is processed previously and get train your algorithm.

Last is predicting text using trained model. Using given sentence or starting sentence to your model try to predict and print the predicted sentence.
