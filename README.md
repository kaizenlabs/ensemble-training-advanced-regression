# Ensemble Models For Advanced Regression

[![Tensorflow](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcT7b9ZDD7lMdkByT-f_RCAqSQYqnq_CpgD16IFrwfmUwWCmdt7H)](https://www.tensorflow.org/beta/guide/effective_tf2)

[![XGBoost](https://upload.wikimedia.org/wikipedia/commons/6/69/XGBoost_logo.png)](https://xgboost.readthedocs.io)

[![Colab](https://camo.githubusercontent.com/52feade06f2fecbf006889a904d221e6a730c194/68747470733a2f2f636f6c61622e72657365617263682e676f6f676c652e636f6d2f6173736574732f636f6c61622d62616467652e737667)](https://colab.research.google.com/github/JohnAntonusMaximus/ensemble-training-advanced-regression/blob/master/Ensemble_Modeling_w_Advanced_Regression.ipynb)

## Background

Rarely is a single machine learning model enough. Typically state of the art machine-learning networks take advantage of a variety of neural networks and machine learning algorithms. Machine learning models can return different types of results and accuracies depending on the dataset and the amount of overfitting from the training data. To work against overfitting, sometimes its best to train a variety of machine-learning models and then use the weighted average of their results as a usable predicton. 

[![Ensemble Model](https://blogs.sas.com/content/subconsciousmusings/files/2017/05/stackedapproach.png)]()

[![Model Stacking](https://blogs.sas.com/content/subconsciousmusings/files/2017/05/modelstacking.png)]()

## Approach

In this example, we're doing to some advanced data visualization to check for outliers, visualize null values, and extract feature importance in sales data for home sales prices. We gain some great insights about what features matter most in the final sales price of a home, as well as use three different types of machine learning models (XGBoost, SVM, and Neural Network) to create an ensemble model with a Gridsearch to return the weighted average prediction

The dataset in its entirety can be found here:
https://www.kaggle.com/c/5407/download-all

# Links

* [KaizenTek](http://www.kaizentek.io) - IT Consulting & Cloud Professional Services