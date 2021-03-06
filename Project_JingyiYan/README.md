Wine Quality
==============================

Data Source: https://archive.ics.uci.edu/ml/datasets/Wine+Quality

Project Description:

This project is aimed to look into the elements or factors that influence the WINE QUALITY by using the multiple classification model like Logistic Regression. In this project, I will fit the Logisitic Regression to make predictions. Using Confusion Martix, Accuracy rate, Error Rate, ROC/AUC as my performance metric analysis of different models. Also, use the hyperparameter tunning like Grid-Search to optimze the model performance. 
Use Pipeline in the "model" file to realize automation workflow.

Performance Metric:
Confusion Matrix, Accuracy Rate, Error rate, ROC/AUC

Data Description:

For more information, read [Cortez et al., 2009].
Input variables (based on physicochemical tests):
1 - fixed acidity
2 - volatile acidity
3 - citric acid
4 - residual sugar
5 - chlorides
6 - free sulfur dioxide
7 - total sulfur dioxide
8 - density
9 - pH
10 - sulphates
11 - alcohol


Output variable (based on sensory data):
12 - quality (score between 0 and 10)

Direct Link:

Final Project Notebook:
https://github.com/Jingyi-Yan/applied_data_science/blob/master/Project_JingyiYan/notebooks/Final%20Project.ipynb

Pipeline:
https://github.com/Jingyi-Yan/applied_data_science/blob/master/Project_JingyiYan/src/models/Pipeline.ipynb

Project Organization
------------

    ├── LICENSE
    ├── Makefile           <- Makefile with commands like `make data` or `make train`
    ├── README.md          <- The top-level README for developers using this project.
    ├── data
    │   └── raw            <- The original, immutable data dump.
    ├── models             <- Trained and serialized models, model predictions, or model summaries
    │
    ├── notebooks          <-Jupyter notebooks. project EDA, preprocessing visualization, and hyperparameters tuning
    │   └── FinalProject.ipynb
    │
    ├── references         <- Data dictionaries, manuals, and all other explanatory materials.
    │
    ├── requirements.txt   <- The requirements file for reproducing the analysis environment, e.g.
    │                         generated with `pip freeze > requirements.txt`
    │
    ├── setup.py           <- makes project pip installable (pip install -e .) so src can be imported
    ├── src                <- Source code for use in this project.
    │   ├── __init__.py    <- Makes src a Python module
    │   ├── models         <- Use Pipeline to fit logistic regression model
    │   │   │                 predictions
    │   │   ├── pipeline.ipynb
    │
    └── tox.ini            <- tox file with settings for running tox; see tox.testrun.org


The work I submitted represents my work and my work alone. I abode by the academic integrity policy and I am aware of the consequences associated with engaging in academic misconduct.

Reference
------------
https://www.kaggle.com/willkoehrsen/intro-to-model-tuning-grid-and-random-search
https://www.kaggle.com/madhurisivalenka/basic-machine-learning-with-red-wine-quality-data

--------

<p><small>Project based on the <a target="_blank" href="https://drivendata.github.io/cookiecutter-data-science/">cookiecutter data science project template</a>. #cookiecutterdatascience</small></p>
