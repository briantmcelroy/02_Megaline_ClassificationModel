# 02_Megaline_ClassificationModel

## About this Project

The Megaline Classification Model project looks at a synthetic dataset of subscriber data to a phone and internet service. Subscribers can be on one of two packages for their phone and internet service. The business has an interest in identifying which users are on which plan, so the goal is to train a machine learning model to predict which of the two plans a given user is most likely paying for.

The project demonstrates (1) how to tune hyperparameters in model training and (2) how to evaluate various model types to determine which will perform best for a given dataset. It uses validation data to tune these models' parameters, and test data to evaluate its accuracy and RMSE. This split gives a production team the power to see how a model performs on novel data and highlight its true predictive power.

## Running it Yourself

The Jupyter notebook is self-contained and reflects the outputs of the code contained within. If you would like to connect to your own environment and run the notebook, or make changes on your own fork of the repo, you may do so after cloning. Make sure the environment is either based in the upper-level folder to which you clone the repo, or be sure to replace the dataset file references with a direct local reference to the /datasets/ folder on your machine. 

The project does not require any dependencies and is stable with Python 3.11.