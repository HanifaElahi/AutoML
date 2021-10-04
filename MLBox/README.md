# MLBox:

- MLBox is a powerful AutoML python library. It provides features such as:

1. Feature selection, missing value imputation, and outliers detection.
2. Optimized and faster data preprocessing.
3. Automatic hyperparameter optimization.
4. Automatic Model selection for classification and regression.
5. Model prediction with interpretations.
6. State-of-the-art predictive models for classification and regression (Deep Learning, Stacking, LightGBM, etc).


In comparison to other AutoML libraries, MLBox does missing value imputation to feature engineering using Entity Embeddings for categorical features. It also tries to make the distribution of train data similar to the test data (drift detection) along with model selection and hyperparameter optimization.

**MLBox focuses on the below three points in particular in comparison to the other libraries:**

1. Drift Identification – A method to make the distribution of train data similar to the test data.
2. Entity Embedding – A categorical features encoding technique inspired from word2vec.
3. Hyperparameter Optimization
 
 
**The entire pipeline of MLBox has been divided into 3 sections/sub-packages.**

1. Pre-Processing
2. Optimisation
3. Prediction

**The pros are: **

1. Automatic task identification i.e Classification or Regression
2. Basic Pre-processing while reading the data
3. Removal of Drifting variables
4. Extremely fast and accurate hyperparameter optimisation.
5. A wide variety of Feature Selection Methods.
6. Minimal lines of code.
7. Feature Engineering via Entity Embeddings


**The cons are: **

1. It is still under active development and things may break or make at any point in time.
2. No support for Unsupervised Learning
3. Basic Feature Engineering. You still have to create your own features.
4. Purely mathematical based feature selection method. This method may remove variables which make sense from the business perspective.
5. Not truly an Automated Machine Learning Library.


## Source : https://www.analyticsvidhya.com/blog/2017/07/mlbox-library-automated-machine-learning/
