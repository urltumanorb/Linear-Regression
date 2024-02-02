# Linear Regression
## What is the project?
This project is a lab that predicting profits by implementing linear regression with one variable. This project can help the restaurant franchises to choose the suitable city to get the higher profits.

## Concepts
Linear regression - It is an algorithm that provides a linear relationship between one or more independent variables and a dependent variable to predict the outcome of future events.
It can be represented as a formula: 

<img width="142" alt="image" src="https://github.com/urltumanorb/Linear-Regression/assets/24932621/9cd06eff-88b2-4635-93bd-508443b3a53b">

cost function - It measures the difference between the predicted values of the model and the actual target values.The goal is to choose the best values for w and b. For one variable, the cost function can be defined as: 

<img width="281" alt="image" src="https://github.com/urltumanorb/Linear-Regression/assets/24932621/2b7ed506-7b91-4fba-8a3d-3974f4ec49ae">

gradient descent - Gradient Descent is an optimization algorithm for finding a local minimum of a differentiable function. In this project, the gradient descent algorithm is:

<img width="223" alt="image" src="https://github.com/urltumanorb/Linear-Regression/assets/24932621/681b4987-37a8-4ca1-b254-0ce24ab798ab">

## Which programing language and packages did I use?
### Language
Python - It is a high-level, general-purpose language. It has concise and expressive syntax, as well as a powerful standard library. It is suitable for various application development domains, including web development, data science, artificial intelligence, and more. In this procject, I used python to accomplish some mechine learning work.

### Packages
numpy - It is the fundamental package for working with matrices in Python.
matplotlib - It is a famous library to plot graphs in Python. It can be used to demonstrate datas.
```
import numpy as np
import matplotlib.pyplot as plt
```

## Dataset
In this project, I used on dataset that consists of two types of data. One is the population of differenties cities. Another is the profit of a restaurant in that city. A negative value for profit indicates a loss. I combined these data to predict the final result.

<img width="122" alt="image" src="https://github.com/urltumanorb/Linear-Regression/assets/24932621/ec4fc3ca-5b89-4346-afac-5ba69d523797">

The datas on the left are the population, the datas on the right are corresponding profits.
