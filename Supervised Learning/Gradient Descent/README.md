# Gradient Descent
Main content of Gradient Descent
* [Gradient Descent]Jupyter notebook file
* Data set: folder containing datasets
* Minimizing a Single Variable Function
* The Problem Description and The General Idea
* Direction of Descent and the Learning Rate
* Testing different choices of the Learning Rate
* Minimizing Functions of Several Variables
* True Gradient Descent
## Introduction 
Gradient descent is an iterative optimization approach for minimizing a loss function in machine learning. Gradient descent is used to discover the optimal set of parameters given the present set of parameters (weights and biases). To update the parameters of our model, we use gradient descent. In Linear Regression, parameters refer to coefficients, while in neural networks, parameters refer to weights.
![image](https://user-images.githubusercontent.com/90750119/166438076-3a17d59f-2ad0-4cf6-b41c-51546c0d38de.png)

* ### Learning rate
The learning rate is a hyperparameter that governs how much the model changes each time the model weights are changed in response to the predicted error. A number too little may result in a protracted training process that becomes stuck, whereas a value too big may result in learning a sub-optimal set of weights too quickly or an unstable training process.
* ### The Loss Function
A loss function is for a single training example. It is also sometimes called an error function. A cost function, on the other hand, is the average loss over the entire training dataset. The optimization strategies aim at minimizing the cost function.
* ### Stochastic gradient descent
  Stochastic gradient descent is an optimization algorithm for minimizing the loss of a predictive model with regard to a training dataset.

## Reference 
* Clare Liu, 5 Concepts You Should Know About Gradient Descent and Cost Function ,https://www.kdnuggets.com/2020/05/5-concepts-gradient-descent-cost-function.html
*  Jason Brownlee, Understand the Impact of Learning Rate on Neural Network Performance ,https://machinelearningmastery.com/understand-the-dynamics-of-learning-rate-on-deep-learning-neural-networks/
*  Khyati Mahendru, A Detailed Guide to 7 Loss Functions for Machine Learning Algorithms with Python Code ,https://www.analyticsvidhya.com/blog/2019/08/detailed-guide-7-loss-functions-machine-learning-python-code/
