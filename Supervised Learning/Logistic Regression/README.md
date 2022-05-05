# Logistic Regression

Main content of Logistic Regression
* [Logistic Regression]Jupyter notebook file
* Data set: The penguin dataset
## Introduction 
The classification technique logistic regression is used to assign observations to a discrete set of classes. Email spam or not spam, online transactions fraud or not fraud, and tumor malignant or benign are some instances of categorization issues. The logistic sigmoid function translates the result of logistic regression into a probability value.

![image](https://user-images.githubusercontent.com/90750119/166831164-994caad6-e405-4025-98c9-d23bacddd761.png)

The logistic regression hypothesis suggests that the cost function be limited to a value between 0 and 1. As a result, linear functions fail to describe it since it might have a value larger than 1 or less than 0, which is impossible according to the logistic regression hypothesis.

## Sigmoid Function
In order to map predicted values to probabilities, we use the Sigmoid function. The function maps any real value into another value between 0 and 1. In machine learning, we use sigmoid to map predictions to probabilities.

![image](https://user-images.githubusercontent.com/90750119/166831348-9e54aeae-f35c-4684-8468-29b9b714efd4.png)

![image](https://user-images.githubusercontent.com/90750119/166831331-5e46b227-7fcf-45e1-920f-646bb4299baf.png)

## Hypothesis Representation
hΘ(x) = β₀ + β₁X

For logistic regression：σ(Z) = σ(β₀ + β₁X)

## Decision Boundary
A decision boundary, also known as a decision surface, is a hypersurface that divides the underlying vector space into two sets, one for each class, in a statistical classification issue with two classes. All points on one side of the decision boundary will be classified as belonging to one class, while those on the other side will be classified as belonging to the other class.
# Reference
1. Decision boundary, From Wikipedia, https://en.wikipedia.org/wiki/Decision_boundary

2. Ayush Pant,Introduction to Logistic Regression,https://towardsdatascience.com/introduction-to-logistic-regression-66248243c148
