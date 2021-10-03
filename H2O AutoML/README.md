# H2O AutoML:

 - H2O is a fully open-source, distributed in-memory machine learning platform with linear scalability. 
 - H2O supports the most widely used statistical & machine learning algorithms, including gradient boosted machines, generalized linear models, deep learning, and many more.
 - AutoML is a function in H2O that automates the process of building a large number of models, with the goal of finding the “best” model without any prior knowledge or effort by the Data Scientist.

**The current version of H2O AutoML trains and cross-validates a default Random Forest, an Extremely-Randomized Forest, a random grid of Gradient Boosting Machines (GBMs), a random grid of Deep Neural Nets, a fixed grid of GLMs, and then trains two Stacked Ensemble models at the end. One ensemble contains all the models (optimized for model performance), and the second ensemble contains just the best performing model from each algorithm class/family (optimized for production use).**

- H2O AutoML tool can do data preprocessing such as numerical encoding, missing values imputation, and other preprocessing workflow. 
- It finally automatically does model selection and hyperparameter tuning and returns with a leaderboard view of the model along with its performance. 
- AutoML also provides a ready to use deployment code.


#### Source: https://www.analyticsvidhya.com/blog/2020/11/exploring-linear-regression-with-h20-automlautomated-machine-learning/

