# API Call Prediction Using Machine Learning Models

This project predicts the number of API calls for the top APIs over a given time span using machine learning models. The models are trained on historical API call data, and predictions are made for future time intervals.

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Requirements](#requirements)
- [Installation](#installation)
- [Usage](#usage)
  - [1. Input Data](#1-input-data)
  - [2. Preprocessing](#2-preprocessing)
  - [3. Model Training and Evaluation](#3-model-training-and-evaluation)
  - [4. Making Predictions](#4-making-predictions)
- [Models Used](#models-used)
- [Results](#results)
- [License](#license)

## Overview

The script:
1. Identifies the top APIs based on the frequency of calls.
2. Prepares historical data for each API.
3. Trains multiple regression models to predict the number of calls for a specified future time span.
4. Outputs predictions using the best-performing model for each API.

## Features

- **Data Preprocessing**: Extracts time-based features like `Hour`, `Minute`, and `Time Since Last Call`.
- **Machine Learning Models**: Trains five different regression models.
- **Performance Evaluation**: Evaluates models using Mean Absolute Error (MAE).
- **Prediction**: Provides predictions for the number of calls for each API over a specified time span.

## Requirements

- Python 3.x
- Required Python Libraries:
  - pandas
  - scikit-learn
  - openpyxl (for exporting Excel files)

Install the required libraries:
```bash
pip install pandas scikit-learn openpyxl
