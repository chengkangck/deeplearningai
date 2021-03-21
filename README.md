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

![image](https://github.com/chengkangck/deeplearningai/blob/main/images/LogReg_kiank.png)

# Logistic Regression Cost Function
The loss function is used to measure the error between the predicted result and the true value.

The simplest way to define the loss function is the squared difference loss:L(Y^, and)=12(Y^- and)2

This is because the square error loss function above is generally a non-convex function (non-convex), which is easy to obtain a local optimal solution when using a low-degree descent algorithm, rather than a global optimal solution. Therefore, a convex function must be selected.

General useL(Y^, and) = - ( andlogY^) + ( 1 - and)log(1−Y^)
when Y=1 Time,L(Y^, and)=−logY^. in caseY^Closer to 1, L(Y^, and)≈0 , Indicating that the prediction effect is better; if Y^ Closer to 0, L(Y^, and)≈+∞ , Which means that the prediction effect is worse;
when Y=0 Time, L(Y^, and)=−log(1−Y^). in caseY^ Closer to 0, L(Y^, and)≈0 , Indicating that the prediction effect is better; if Y^ Closer to 1, L(Y^, and)≈+∞ , Which means that the prediction effect is worse;
Our goal is to minimize the loss of sample points Loss Function, the loss function is for a single sample point.

# Gradient Descent on m Examples

# Vectorization

# Broadcasting in Python
