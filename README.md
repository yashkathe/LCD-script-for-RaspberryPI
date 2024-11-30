# Cirrhosis Prediction Using Neural Networks

<img src="https://www.startstemcells.com/wp-content/uploads/2024/07/liver-2.jpg" height="300" alt="cirrhosis stages">

## Overview

In this project I have developed a predictive model to classify cirrhosis into four
categories using a neural network built with PyTorch.

I'm using the [Cirrhosis Prediction Dataset](https://www.kaggle.com/datasets/fedesoriano/cirrhosis-prediction-dataset/data).

## What is Cirrhosis?

Cirrhosis is a chronic liver disease characterized by scarring (fibrosis) of the
liver tissue, leading to impaired liver function.  
Commonly caused by long-term liver damage from factors like alcohol abuse, hepatitis, and fatty liver disease  
Early detection and classification of cirrhosis stages are essential
for timely intervention.

## Files

### Random Forest

- [Random Forest with 275 estimators](./random_forest.ipynb)
=> accuracy = 44%

### Neural Network using Pytorch

- [Neural Network with Gradient Descent](./cirrhosis_prediction_pytorch_gd.ipynb)
- [Neural Network with Stochastic Gradient Descent](./cirrhosis_prediction_pytorch_batch_sgd.ipynb)
- [Neural Network with Stochastic Gradient Descent and Dropout Layers](./cirrhosis_prediction_pytorch_sgd_and_dropout.ipynb)

#### Plots for Neural Network with Gradient Descent

![Accuracy Plot](./readme_content/accuracy_1.png)
![Loss Plot](./readme_content/loss_1.png)

#### Plots for Neural Network with Stochastic Gradient Descent

![Accuracy Plot](./readme_content/accuracy_2.png)
![Loss Plot](./readme_content/loss_2.png)

#### Plots for Neural Network with Stochastic Gradient Descent and Dropout Layers

![Accuracy Plot](./readme_content/accuracy_3.png)
![Loss Plot](./readme_content/loss_3.png)

### Neural Network From Scratch

[Shallow Neural Network using Numpy only](./from_scratch_neural_network.ipynb)

This file includes complete data preprocessing

1. Drop columns with excessive missing values
2. Fill rows with missing values
3. Data Mapping
4. Handle Outliers
5. Normalizing the data
6. OverSampling with SMOTE
