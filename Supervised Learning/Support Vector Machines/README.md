# Support Vector Machines

Main content of Support Vector Machines

* [Support Vector Machines](/guides/content/editing-an-existing-page) Jupyter notebook file
* Data set: Cancer from sklearn
## Introduction 
SVMs are supervised machine learning algorithms that are used for classification and regression analysis. The SVM is capable of both linear and nonlinear classification. The Kernel function is used to accomplish nonlinear classification. Homogeneous polynomial, complex polynomial, Gaussian radial basis function, and hyperbolic tangent function are the kernels in nonlinear classification. The Gaussian kernel, which has a single parameter, performs exceptionally well in SVM. Because the SVM approach surpasses the others, it is the most often utilized machine learning methodology, particularly in industrial settings.

![image](https://user-images.githubusercontent.com/90750119/166839835-fef5ae18-f071-4752-b1bd-e8299d3cc02f.png)
## Linear SVM
We are given a training dataset of  n points of the form
![image](https://user-images.githubusercontent.com/90750119/166840062-47625800-e339-4995-ac11-2bd6f26d7b88.png)

Any hyperplane can be written as the set of points satisfying ![image](https://user-images.githubusercontent.com/90750119/166840139-3eff720d-8d26-45ff-bd7d-e4a15762b8b8.png)
## Nonlinear Kernels
The original maximum-margin hyperplane algorithm proposed by Vapnik in 1963 constructed a linear classifier. However, in 1992, Bernhard Boser, Isabelle Guyon and Vladimir Vapnik suggested a way to create nonlinear classifiers by applying the kernel trick 
## Computing the SVM classifier
Computing the (soft-margin) SVM classifier amounts to minimizing an expression of the form
![image](https://user-images.githubusercontent.com/90750119/166840238-6427b7f3-100c-4e95-9c42-c846826dbea2.png)

## Modern methods
Recent algorithms for finding the SVM classifier include sub-gradient descent and coordinate descent.
# Reference
Support Vector Machine, https://www.sciencedirect.com/topics/engineering/support-vector-machine

Support-vector machine, From Wikipedia, https://en.wikipedia.org/wiki/Support-vector_machine
