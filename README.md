# Regression Model Comparison on Tabular Data

This project started as a simple regression exercise, but I turned it into a small experiment to understand how different models behave on tabular data.

Instead of focusing on complex models, the goal here is to compare basic approaches and see where they work and where they fail.

## What this project does

- Trains multiple regression models on the same dataset
- Uses RMSE to evaluate performance
- Compares results across models
- Visualizes the differences

## Models included

- Dummy Regressor (baseline)
- Linear Regression
- Random Forest

## Why I built this

A lot of machine learning work jumps straight to more complex models, but that often hides what is actually happening.

I wanted to see:

- How much better real models are compared to a simple baseline  
- Whether more complex models always perform better  
- How stable the results are on tabular data  

## What I learned

- Baselines matter more than expected  
- More complex models are not always better  
- Performance can vary depending on how the data is split  

## How to run

```bash
python main.py
