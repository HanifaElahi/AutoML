# Auto-Sklearn:

- It is built around the sci-kit learn library.
- It automatically searches for the right Machine Learning models fitting the data.
- Auto-sklearn builds an ensemble of all models tested during the global optimization process.
- In order to speed up the optimization process, auto-sklearn uses meta-learning to identify similar datasets and use the knowledge gathered in the past.
- Auto-Sklearn wraps a total of 15 classification algorithms, 14 feature preprocessing algorithms, and takes care of data scaling, the encoding of categorical parameters, and missing values.


### Advantages
- Along with data preparation and model building, it also learns from models that have been used on similar datasets and can create automatic ensemble models for better accuracy.
- Uses Bayesian Optimization for faster results.

### Disadvantages
- auto-sklearn is completely automatic and black-box. 
- It searches a vast space of models and constructs complex ensembles of high accuracy, taking a substantial amount of computation and time in the process. The goal of auto-sklearn is to build the best model possible given the data.
