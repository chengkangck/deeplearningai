# Logistic Regression
Logistic regression is an algorithm for binary classification.

The parameters used in logistic regression are as follows:

- The input feature vector:x∈Rnx,among them nxIs the number of features;

- Labels used for training:Y∈0,1

- Weights:w∈Rnx

- Bias: b∈R

- Output:Y^= σ(wTx+b)

- Sigmoid function:s = σ(wTx + b ) = σ( with)=11+e- with

For will wTx+b Bound to [0,1] In the meantime, the Sigmoid function is introduced, and the value range of the Sigmoid function is [0,1]。

Logistic regression can be seen as a very small neural network. The following figure is a typical example:
