# Auto-ViML:

- Auto-ViML stands for Automated Variant Implementation Machine Learning. 
- A limitation TPOT AutoML tool was that it expects a dataset in a numerical format.Any missing values handling and data cleaning stuff should be completed prior to the TPOT implementation.
- AutoViML overcomes this problem, as it takes care of encoding dataset, feature selection, and other data cleaning activities. --- AutoViML is comparatively faster than TPOT and generates several graphical results along with model selection and hyperparameter optimization.

Auto_ViML was designed for building High Performance Interpretable Models with the fewest variables. 

- The "V" in Auto_ViML stands for Variable because it tries multiple models with multiple features to find you the best performing model for dataset. 
- The "i" in Auto_ViML stands for "interpretable" since Auto_ViML selects the least number of features necessary to build a simpler, more interpretable model. 

- In most cases, Auto_ViML builds models with 20-99% fewer features than a similar performing model with all included features (this is based on my trials. Your experience may vary).



## Features:
1. SMOTE -> use SMOTE for imbalanced data. Just set Imbalanced_Flag = True
2. Auto_NLP: It automatically detects Text variables and does NLP processing on those columns
3. Date Time Variables: It automatically detects date time variables and adds extra features
4. Feature Engineering: Now you can perform feature engineering with the available featuretools library.


### Auto-ViML helps in :
1. helps in data cleaning(missing values, formatting variables, adding variables,etc).
2. Classifies variables automatically(numeric vs categorical vs NLP text vs date-time variables).
3. Performs feature reduction automatically(uses XGBoost repeatedly to perform feature selection).
4. Produces model performance results as graphs automatically(set verbose = 1 (or) 2).
5. Allows you to use the featuretools library to do Feature Engineering.

#### Source: https://pypi.org/project/autoviml/ 

