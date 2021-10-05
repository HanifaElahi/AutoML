# FLAML:

- FLAML is a lightweight Python library that finds accurate machine learning models automatically, efficiently and economically. 
- It frees users from selecting learners and hyperparameters for each learner. 
- It is fast and economical. 
- The simple and lightweight design makes it easy to extend, such as adding customized learners or metrics. 
- FLAML is powered by a new, cost-effective hyperparameter optimization and learner selection method invented by Microsoft Research. - FLAML leverages the structure of the search space to choose a search order optimized for both cost and error. For example, the system tends to propose cheap configurations at the beginning stage of the search, but quickly moves to configurations with high model complexity and large sample size when needed in the later stage of the search. For another example, it favors cheap learners in the beginning but penalizes them later if the error improvement is slow. 
- The cost-bounded search and cost-based prioritization make a big difference in the search efficiency under budget constraints.

Nowadays, many businesses started building machine learning embedded applications, and it costs a lot to select a single machine learning model from a variety of machine learning models. After choosing a model, it is also time-consuming to select the best parameters for every dataset. To solve this problem, Microsoft built an AutoML system which is mainly focused on:

- Model selection
- Hyperparameter tuning
- Feature engineering
- Neural architecture search
- Model compression 