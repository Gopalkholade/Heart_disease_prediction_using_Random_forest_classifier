# Heart Disease prediction using Machine Learning.

## Introduction

Heart diseases is a term covering any disorder of the heart.
Heart diseases have become a major concern to deal with as studies show that the number of deaths due to heart diseases have increased significantly over the past few decades in India, in fact it has become the leading cause of death in India.

A study shows that from 1990 to 2016 the death rate due to heart diseases have increased around 34 per cent from 155.7 to 209.1 deaths per one lakh population in India.

Thus preventing Heart diseases has become more than necessary.
Good data-driven systems for predicting heart diseases can improve the entire research and prevention process, making sure that more people can live healthy lives.
This is where Machine Learning comes into play.
Machine Learning helps in predicting the Heart diseases, and the predictions made are quite accurate.

Problem Description :

A dataset is formed by taking into consideration some of the information of 918 individuals.
The problem is : based on the given information about each individual we have to calculate that whether that individual will suffer from heart disease.

## Dataset :

The dataset consists of 779 individuals data.
There are 15 columns in the dataset, however the first column name is not a good parameter as far as machine learning is considered so, there are effectively 14 columns.

1. Age : The age of a person, ranging from 28 to 77 years old.
2. Sex : Is the person Male or Female?
3. ChestPainType : There are four types in this label : ATA, NAP, ASY, TA.
4. RestingBP : Ranging from 0 to 200.
5. Cholesterol : Ranging from 0 to 603.
6. FastingBS : Does the person get FastingBS? (0 or 1)
7. RestingECG : There are three types in this label : Normal, ST, LVH.
8. MaxHR : Ranging from 60 to 202.
9. ExerciseAngina : Does the person get ExerciseAngina? (Yes or No)
10. Oldpeak : Ranging from -2.6 to 6.2.
11. ST_Slope : There are three types in this label : Up, Flat, Down.
12. HeartDisease : Is the person illness? (Yes or No)

## Model Training and Prediction : 
We can train our prediction model by analyzing existing data because we already know whether each patient has heart disease. This process is also known as supervision and learning. The trained model is then used to predict if users suffer from heart disease. The training and prediction process is described as follows:

## Splitting: 
First, data is divided into two parts using component splitting. In this experiment, data is split based on a ratio of 80:20 for the training set and the prediction set. Test train split is used for creating Trainning and testing data.

Random Forest Classifier is used for classification Purpose.

## Cross-Validation :
For cross validation we used Stratified-KFold 

## Prediction:
The two inputs of the prediction component are the model and the prediction set. The prediction result shows the predicted data, actual data, and the probability of different results in each group.

## Feature_Importance :
Feature importance is evaluated with Random Forest function feature_importance_

## Evaluation: 
Classification replort is been used for evaluation.