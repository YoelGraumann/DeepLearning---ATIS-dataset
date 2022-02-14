# DeepLearning---ATIS-dataset
In this notebook I will perform intent classification using three different models to see which one is better for this task. I will be using PyTorch.
the data I used for this notebook is provided. The names are testlabel, testseq.in, train_label, trainseq.in

In this notebook you can expect to see:
  * Uploading the data and understanding it
  * Preprocessing the data and some feature engineering
  * Creating my own tokenization algorithm
  * Creating my own accuracy, confusion matrix and training functions
  * Feeding the data into the models and performing statistical inference

The models I used for intent classification  are:
  * Simple ANN model
  * BiDirectional LSTM model based off of [Yu Wang, Yilin Shen & Hongxia Jin](https://arxiv.org/pdf/1812.10235v1.pdf)
  * BERT transformer model. I used a pretrained model and changed it up a bit to work for my own problem.

I think Natural Language Processing is very interesting and hope to work on more similar projects.
