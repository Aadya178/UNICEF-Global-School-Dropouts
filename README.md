<!-- INTRODUCTION -->

# UNICEF Global School Dropouts

[![forthebadge](http://forthebadge.com/images/badges/made-with-python.svg)](http://forthebadge.com)

*[UNICEF](https://www.unicef.org/education) says, on any given school day, over 1 billion children around the world head to class. More children and adolescents today are enrolled in pre-primary, primary and secondary education than ever before.*

<p align="center">
<img src="https://user-images.githubusercontent.com/55178494/141785815-a5feb025-3cbd-4b6f-9d1d-b60c34d528bf.png" height="400" width="700">
</p>

*Yet an estimated 617 million children and adolescents around the world are unable to reach minimum proficiency levels in reading and mathematics, even though two thirds of them are in school. 11 per cent of primary-school-aged children and 20 per cent of lower-secondary-aged children are not in school at all*

<!-- ABOUT THE PROJECT -->

## Overview

<details>
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
      <a href="#predicted-output">Predicted Output</a>
    </li>
  </ul>
</details>

<!-- DETAILED EXPLANATION -->

## Problem Statement
🤔
> UNICEF has collected the pupil dropout rate at different educational levels (primary, lower secondary and upper secondary) through various sources over the course of 10 years.
> This dataset contains dropout rates based on several parameters (gender, living conditions and financial conditions) in different regions around the globe.
> It finally mentions the total pupil dropout rate in these regions.
> The issue is to understand the dropout rate trends globally.

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
> The dataset will be analyzed in the following manner.
> 
> <p align="center">
  <img src="process flow.png">
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
> The data has been analyzed using the following 3 methods:
> 
> 1. [Jupyter Notebook](https://github.com/Aadya178/NOAA-Check-Reef-Bleaching/blob/main/NOAA%20Reef%20Bleaching.ipynb)

## Model Used
🤖
> The output is, given certain factors (which may cause reef bleaching), whether or not the coral reef has actually been bleached.
> 
> The model has been trained using Logistic Regression algorithm.
> 
> The target variable is `Bleaching`.

## Predicted Output
💯 
> 
> The accuracy of the output prediction is greater than 96%.
> 
> The model's accuracy is being evaluated using K-fold cross-validation.
> 
> The evaluation metrics include RMSE(Root Mean Square Error) and R2 score.



👋🏻 Hi! Thanks for stopping by. Give it a ⭐ if you like it!
