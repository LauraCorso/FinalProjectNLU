# Language Modeling with RNN
Final project of the course *Natural Language Understanding* at University of Trento (year 2022).

## Description
The aim of this project is to develop a Recurrent Neural Network to deal with the task of Language Modeling.
To realize the task, two different RNN models are developed: a baseline model and an improved model. The latter is an improvement of the former one through the application of the
following regularization techniques:
- dropout on the hidden-to-hidden connections of the RNN.
- Variational dropout (as described in the work by *S. Merity, N. S. Keskar, and R. Socher, “Regularizing and
optimizing LSTM language models,” CoRR, vol. abs/1708.02182,
2017, http://arxiv.org/abs/1708.02182*).
- L-2 weight decay.
