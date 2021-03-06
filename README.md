<!-- INTRODUCTION -->

# UNICEF Global School Dropouts

[![forthebadge](http://forthebadge.com/images/badges/made-with-python.svg)](http://forthebadge.com)

*[UNICEF](https://www.unicef.org/education) says, on any given school day, over 1 billion children around the world head to class. More children and adolescents today are enrolled in pre-primary, primary and secondary education than ever before.*

<p align="center">
<img src="https://user-images.githubusercontent.com/55178494/141785815-a5feb025-3cbd-4b6f-9d1d-b60c34d528bf.png" height="400" width="700">
</p>

*Yet an estimated 617 million children and adolescents around the world are unable to reach minimum proficiency levels in reading and mathematics, even though two thirds of them are in school. 11 per cent of primary-school-aged children and 20 per cent of lower-secondary-aged children are not in school at all!*

<!-- ABOUT THE PROJECT -->

## Overview

<details open="open">
  <summary>Contents</summary>
  <ul>
    <li>
      <a href="#problem-statement">Problem Statement</a>
    </li>
    <li>
      <a href="#objective">Objective</a>
    </li>
    <li>
      <a href="#dataset">Dataset</a>
    </li>
    <li>
      <a href="#process-flow">Process Flow</a>
    </li>
    <li>
      <a href="#libraries-used">Libraries Used</a>
    </li>
    <li>
      <a href="#data-analysis-and-visualization">Data Analysis and Visualization</a>
    </li>
    <li>
      <a href="#model-used">Model Used</a>
    </li>
    <li>
      <a href="#model-evaluation">Model Evaluation</a>
    </li>
    <li>
      <a href="#result">Result</a>
    </li>
  </ul>
</details>

<!-- DETAILED EXPLANATION -->

## Problem Statement
🤔
> UNICEF has collected the pupil dropout rate at different educational levels (primary, lower secondary and upper secondary) through various sources over the course of 10 years.
> This dataset contains dropout rates at different educational levels based on several parameters (gender, living conditions and financial conditions) in different regions around the globe.
> It finally mentions the total pupil dropout rate in these regions.
> The task is to analyze the dataset attributes and thus understand the dropout trends globally.

## Objective
🎯
> The aim is to build a model that shows the significance of each factor in predicting the total dropout rate.
> This can be further used to identify the key areas to work on to bring down the `Total Dropout rate` in different regions.


## Dataset
📊
> The dataset contains the following attributes:
> 
> * Region
> * UNICEF Sub-region 1	
> * Development Regions	
> * Female Dropout Rate
> * Male Dropout Rate
> * Rural Dropout Rate
> * Urban Dropout Rate
> * Poorest Dropout Rate
> * Poor Dropout Rate
> * Middle Segment Dropout Rate
> * Rich Dropout Rate
> * Richest Dropout Rate
> * Data Source	
> * Time period
> * Educational level	
> * Total Dropout Rate


## Process Flow
🎞️
> The dataset has been analyzed in the following manner.
> <p align="center">
  <img src="process-flow.png">
  </p>
  
## Libraries Used
📚
> [`numpy`](https://numpy.org/doc/stable/)  adds support for large, multi-dimensional arrays and matrices, along with a large collection of high-level mathematical functions to operate on these arrays.
> 
> [`matplotlib`](https://matplotlib.org/stable/) is a plotting library for the Python programming language and its numerical mathematics extension NumPy. It provides an object-oriented API for embedding plots into applications using general-purpose GUI toolkits.
> 
> [`scipy`](https://scipy.github.io/devdocs/index.html) is used for scientific computing and technical computing. It contains modules for optimization, linear algebra, integration, interpolation, special functions, FFT, signal and image processing, ODE solvers and other tasks.
> 
> [`pandas`](https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.DataFrame.html) is for data manipulation and analysis. In particular, it offers data structures and operations for manipulating numerical tables and time series.
> 
> [`sklearn`](https://scikit-learn.org/stable/) or scikit-learn features various classification, regression and clustering algorithms and is designed to interoperate with the Python numerical and scientific libraries NumPy and SciPy.
> 
> [`seaborn`](https://seaborn.pydata.org/) is a Python data visualization library based on matplotlib. It provides a high-level interface for drawing attractive and informative statistical graphics.

## Data Analysis and Visualization
👀
> The data has been analyzed using [Jupyter Notebook](https://github.com/Aadya178/UNICEF-Global-School-Dropouts/blob/main/UNICEF%20Global%20School%20Dropouts.ipynb).

## Model Used
🤖
> The target variable is `Total Dropout Rate`.
>
> Since the target variable's range can be any value from 0-100% hence it is a Regression problem.
> 
> Thus, the model has been trained using Multiple Linear Regression algorithm.

## Model Evaluation
💯 
> 
> The accuracy of the output prediction is greater than 99%.
> 
> The model's accuracy is being evaluated using K-fold cross-validation.
> 
> The evaluation metrics include RMSE(Root Mean Square Error) and R2 score.

## Result
🏁
>The most important predictors for the `Total Dropout Rate` of pupils in different regions globally are:
>
> * Female dropout rate
>
> * Male dropout rate
>
> * Rural dropout rate
>
> * Urban dropout rate
>
> * Poorest dropout rate
>
> * Poor dropout rate
>
> * Middle Segment dropout rate
>
> * Rich dropout rate
>
> * Richest dropout rate

> While the other factors:
>
> * Region
> 
> * UNICEF Sub-region 1
>
> * Development Regions
>
> * Data Source
>
> * Time Period
>
> * Educational Level
> don't have a significant impact on the Total dropout rate.

> The analysis shows that the students' gender, living conditions and financial wellness are crucial to determine the total dropout rates and are hence the key areas for development. While the global regions and the educational level along with other factors are not very important.
> 
> Thus, the government authorities and related organizations should strive to educate children from different backgrounds alike.
> 
> Since the model has an extremely high accuracy rate of more than 99%, it can be used to predict the total dropout rates in the future too and thus assist in bringing them down.



👋🏻 Hi! Thanks for stopping by. Give it a ⭐ if you like it!
