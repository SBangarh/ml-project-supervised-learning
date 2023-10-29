# machine_learning_project-supervised-learning

## Overview
The purpose of this project is to apply supverised learning techniques to a diabetes dataset. Also to practice EDA which is the most important step.


## Goals
1. Apply supervised machine learning techniques
2. I want to focus on EDA as well, it is one of my weak point
3. practice using more function as opposed to hard coding
4. have fun

## Process
I applied EDA techniques to better understand the dataset. Once I better understood the dataset, I preprocessed the data by replacing outliers with the approriate median value. I also scaled the data here as well. I chose to to a Logistic Regression and a Random Forest on the data. Prior to fitting the models, I performed a grid search for hyperparametes.

## Results

The average age, BMI, and glucose was all higher for people with diabetes. I found the Logistic Regression performed better than the Random Forest on test data. In addition, both models had similar top five contributing factors, but in different order. Glucose was the biggest contributer in both. 

## Future Goals

I would like to tune the models a bit more. I want to select relevent features and perform backward or forward selection, but I struggled with building a function for this, so I need to put in some work.

## Challenges

I struggled with knowing what was going on under the hood of the models I chose and the multiude of parameters that could be passed.
I struggled with writing functions that could have helped me better optimize the models
This was a big learning curve for me in general, but fun nevertheless.

## Acknowledgements
I would like to acknowledge the authors/contributers of the following libraries: Pandas, Numpy, Matplotlib, Seaborn, and scikit-learn. This project would not have happened without these libraries. 