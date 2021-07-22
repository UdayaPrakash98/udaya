1.machine learning:

machine learning is a term of building a model using equations for data ..which will learn from data to predictive analysis

2.Can you think of 4 distinct types of issues where it shines

overfitting,underfitting,lacking of a data , irrespective of data

3.What is a labeled training set, and how does it work?

labeled training set is also called depedent value or y axis 
which is need to be find using feature values to predict the output

4.What are the two most important tasks that are supervised?

two most common is regression and classification

5.Can you think of four examples of unsupervised tasks?


```python
clustering,dimension reduction,visualization (k-means,herrarical,Dbscan,nave bayes)
```

6.State the machine learning model that would be best to make a robot walk through various unfamiliar terrains?

Reinforcement learning may be used which is hit and trial method which robort learn from mistakes

7.Which algorithm will you use to divide your customers into different groups?

K-means clustering is unsupervised learning which is used to segment the customers in form of clusters

8.Will you consider the problem of spam detection to be a supervised or unsupervised learning problem?


```python
it can be done by using classification of supervised model 
```

9.What is the concept of an online learning system


```python
online learning system is used to learn informations via internet from our comfort through computer
```

10.What is out-of-core learning, and how does it differ from core learning

Out-of-core learning refers to a set of algorithms working with data that cannot fit into the memory of a single computer, 
but that can easily fit into some data storage such as a local hard disk or web repository

11.What kind of learning algorithm makes predictions using a similarity measure

instance based algorithm or finding similarities while training

12.What's the difference between a model parameter and a hyperparameter in a learning algorithm?

model parameter is used automaticaaly by data while in use while
hyperparameter is used manually to evaluate or perform best accuracy 

13.What are the criteria that model-based learning algorithms look for?
What is the most popular method they use to achieve success? What method do they use to make predictions?
The goal for a model-based algorithm is to be able to generalize to new examples. To do this, model based algorithms search for optimal values for the model's parameters, often called `theta`. This searching, or "learning", is what machine learning is all about. Model-based system learn by minimizing a cost function that measures how bad the system is at making predicitons on new data, plus a penalty for model complexity if the model is regularized. To make a prediction, a new instance's features are fed into a hypothesis function which uses the minimized `theta` found by repeatedly running the cost function.

14) Can you name 4 of the main challenges in Machine Learning?
    Not gathering enough data, or sampling noise. non-representative data 


15) If your model performs great on the training data but generalizes poorly to new instances, what is happening? Can you name 3 possible solutions?
This is a case where the model is overfitting the training data. To couteract overfitting, we can reduce the complexity of the model by removing features or constraining the parameters. We could gather more data. Finally we can reduce noisiness in the data by fixing errors and removing outliers.

16) What is a test set and why would you want to use it?
When we want to know how well our model generalizes to new cases we prefer to use a test set instead of actually deploying the system. To build the test set we split the training data (50-50, 60-40, 80-20 are common splits) into a training set and test set. Our model is training with the training set. Then we use the model to run predictions on the test set. Our error rate on the test set is called the `generalization error` or `out-of-sample error`.

 17) What is the purpose of a validation set?
Let's say we have a linear model and we want to perform some hyperparameter tuning to reduce the generalization error. One way to do this 100 different models with 100 different hyperparameter values using the training set and finding the generalization error with the test set. You find the best hyperparameter value gives you 5% generalization error.
valdiation set used to valdiate the test set 

18) What can go wrong if you tune hyperparameters using the test set?
Your model will not be generalizable to new examples.

19) What is cross-validation and why would you prefer it to a validation set?
Cross-validation helps us compare models without wasting too much training data in the validation set.

```python

```


```python

```
