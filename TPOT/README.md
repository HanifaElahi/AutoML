# TPOT:

- TPOT is a Python Automated Machine Learning tool that optimizes machine learning pipelines using genetic programming.
- POT expects a cleaned dataset, it does feature processing, model selection, and hyperparameter optimization to return the best performing model.
- It stands for Tree-based Pipeline Optimization Tool and was developed by Randal S. Olson and others at the University of Pennsylvania.
- This is better than brute forced GridSearch, as it has been shown that evaluating random parameters within a grid often discovers the optimal pipeline more efficiently. 


#### TPOTs parameters:
- generations: This is the number of iterations to the run pipeline optimization process.
- population size: Number of individuals to retain in the genetic programming population every generation.
- offspring size: Number of offspring to produce in each genetic programming generation.
- cv: Cross-validation generator for pipeline evaluation
- config_dict: Python dictionary for customizing the operators and parameters that are searched during the optimization process.

- On the whole, TPOT will do “population size + generations * offspring size” pipelines to evaluate.
- Without modifying these parameters, TPOT evaluates 10,000 pipeline configurations with cross validation before finishing. 
- Once TPOT has finished running it allows you to export a .py file with the best pipeline that it could find containing all the information you need to run it.


TPOT will automate the most tedious part of machine learning by intelligently exploring thousands of possible pipelines to find the best one for your data.

<img src = https://github.com/EpistasisLab/tpot/blob/master/images/tpot-ml-pipeline.png>

[Source : https://github.com/EpistasisLab/tpot](https://github.com/EpistasisLab/tpot)

Once TPOT is finished searching (or you get tired of waiting), it provides you with the Python code for the best pipeline it found so you can tinker with the pipeline from there.

<img src = https://github.com/EpistasisLab/tpot/blob/master/images/tpot-pipeline-example.png>
[Source : https://github.com/EpistasisLab/tpot](https://github.com/EpistasisLab/tpot)
