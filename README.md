# Company Revenue Growth Analysis & Prediction

## Overview
This project analyzes the relationship between a company's employee count 
and its revenue, and builds classification models to predict whether a 
company will achieve positive revenue growth in 2023.

## Dataset
- **Source:** Statista (600 e-commerce companies)
- **File:** `Revenue Prediction Dataset.csv`
- **Features:** Revenue (2022), Employees, Last Revenue Growth, 
  Industry, Location, Founding Year

## Models Built
- Linear Regression — predicts Revenue in 2022
- Logistic Regression — predicts positive revenue growth
- Random Forest — predicts positive revenue growth  
- Naive Bayes — predicts positive revenue growth

## Files
| File | Description |
|------|-------------|
| `Revenue Prediction Dataset.csv` | Raw dataset |
| `Project_Classification.Rmd` | Full R Markdown analysis |
| `README.md` | This file |

## Requirements
R packages: `dplyr`, `ggplot2`, `caret`, `randomForest`, `e1071`, 
`pROC`, `moments`, `reshape2`, `gridExtra`, `patchwork`, `glmnet`

## How to Run
1. Clone this repository
2. Open `Project_Classification.Rmd` in RStudio
3. Ensure `Revenue Prediction Dataset.csv` is in the same folder
4. Click **Knit** to generate the HTML report