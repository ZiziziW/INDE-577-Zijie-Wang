# Ensemble Learning
Main content of Ensemble Learning
* [Ensemle Learning](/guides/content/editing-an-existing-page) Jupyter notebook file
* Data set: The penguin dataset
## Introduction 
Ensemble learning is a general meta approach to machine learning that seeks better predictive performance by combining the predictions from multiple models.  Other applications of ensemble learning include assigning a confidence to the decision made by the model, selecting optimal (or near optimal) features, data fusion, incremental learning, nonstationary learning and error-correcting. 
![image](https://user-images.githubusercontent.com/90750119/166436671-1cb9c23f-70fa-461a-81ea-d229f3a4d544.png)

* ### Bagging 

  Bagging, also known as bootstrap aggregation, is the ensemble learning method that is commonly used to reduce variance within a noisy dataset. In bagging, a random sample of data in a training set is selected with replacement—meaning that the individual data points can be chosen more than once.
  
* ### Random Forest

  Random forest is a Supervised Machine Learning Algorithm that is used widely in Classification and Regression problems. It is created from subsets of data and the final output is based on average or majority ranking and hence the problem of overfitting is taken care of.
  ![1651572421(1)](https://user-images.githubusercontent.com/90750119/166436093-1f26b399-2b8c-4cbe-979e-4ab73b0ddeed.png)
* ### Gradient Boosting
   The principle behind boosting algorithms is first we built a model on the training dataset, then a second model is built to rectify the errors present in the first model. Let me try to explain to you what exactly does this means and how does this works. When the target column is continuous, we use Gradient Boosting Regressor whereas when it is a classification problem, we use Gradient Boosting Classifier. 
* ## Reference 
* Robi Polikar (2009), Scholarpedia,http://www.scholarpedia.org/article/Ensemble_learning
* IBM Cloud Education, https://www.ibm.com/cloud/learn/bagging#:~:text=Bagging%2C%20also%20known%20as%20bootstrap,be%20chosen%20more%20than%20once.
* Sruthi E R, Understanding Random Forest, https://www.analyticsvidhya.com/blog/2021/06/understanding-random-forest/
* Anshul Saini, Gradient Boosting Algorithm: A Complete Guide for Beginners,https://www.analyticsvidhya.com/blog/2021/09/gradient-boosting-algorithm-a-complete-guide-for-beginners/
