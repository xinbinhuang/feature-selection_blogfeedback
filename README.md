# UCL Machine Learning dataset - BlogFeedback

## Overview

This project performs a feature and model selection on the UCI machine learning `BlogFeedback` dataset. The methods used include ridge, lasso, and elastic net regressions. Given the performance metrics, 42 features are selected from 280 features via Lasso regression.

## Data Description

Detailed documentation and data source are available here [UCL - BlogFeedback Data Set ](https://archive.ics.uci.edu/ml/datasets/BlogFeedback)

The original dataset includes one `train` set, `blogData_train.csv` and multiple small `test` set. I combined all the test set into one test set called `test.csv`. All analysis are based on the `blogData_train.csv` and `test.csv`. Also the `data-attribute-description.md` describe the names of the features which correspond to the columns of the dataset.

## Procedure of analysis
To reproduce the whole analysis, you need to clone the repo into your local machine. 

Then open the jupyter notebook in `src/analysis-script.ipynb`, and `run all` from top to bottom.

## Final report
The final report can be found in the `doc` folder [report](doc/report.ipynb)

## Dependencies
- Python - 3.6
- Jupyter notebook - 1.0.0
- Numpy - 1.13.3
- Pandas - 0.22.0
- matplotlib - 2.1.1
- scikit-learn - 0.19.1
