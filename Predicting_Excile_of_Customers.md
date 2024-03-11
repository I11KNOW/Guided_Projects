## Overview

This project focuses on predicting customer exile using the Random Forest Classifier algorithm. 

The goal is to identify customers who are likely to stop using a service or product, allowing businesses to take proactive measures to retain them.

## Dataset

The dataset used for this project contains historical customer data, including features such as geographies, tenure, activity by the member, and salary. 

Each sample is labeled with a binary indicator of whether the customer has exited (1) or remained active (0).

## Model Architecture

The Random Forest Classifier is an ensemble learning algorithm that constructs multiple decision trees during training and outputs the mode of the classes (classification) or the mean prediction (regression) of the individual trees. 

It is well-suited for classification tasks and offers robustness against overfitting.

## Preprocessing

Before training, the dataset undergoes preprocessing steps such as handling missing values, encoding categorical variables, and smotting the target.

Additionally, feature selection techniques may be employed to identify the most relevant predictors for customer exile.
