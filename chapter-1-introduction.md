# 1.1 Polynomial Curve Fitting

> The result of running the machine learning algorithm can be expressed as a function **y(x)** which takes a new digit image **x** as input and that generates an output vector y, encoded in the same way as the target vectors.

Mapping.

> The ability to categorize correctly new examples that differ from those used for training is known as generalization.

What we want is to predict new data based on data we have.

> Applications in which the training data comprises examples of the input vectors along with their corresponding target vectors are known as *supervised learning* problems.

## Over-fitting Problem

Increasing size of the data set reduces the over-fitting problem.

# 1.2 Probability Theory

The Rules of Probability

1. sum rule $$p(X)=\sum_Yp(X,Y)$$
2. product rule $$p(Y|X)=p(Y|X)p(X)$$

Bayes' theorem $$p(Y|X)=\frac{p(X|Y)p(Y)}{p(X)}$$
The denominator in Bayes' theorem is $$p(X)=\sum_Yp(X|Y)p(Y)$$

**prior probability**
**posterior probability**

In the machine learning literature, the negative log of the likelihood function is called an error function. Because the negative logarithm is a monotonically decreasing function, maximizing the likelihood is equivalent to minimizing the error.

### 1.2.4 The Gaussian distribution
