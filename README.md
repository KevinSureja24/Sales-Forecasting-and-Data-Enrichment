# -Sales-Forecasting-and-Data-Enrichment

# Sales Prediction using CatBoost and UPGini

This repository contains code for training a sales prediction model using CatBoost regressor and enriching features using UPGini, a feature engineering library.

## Getting Started

To get started with this project, follow the instructions below:

### Prerequisites

Ensure you have Python installed on your machine. You can download it from [python.org](https://www.python.org/downloads/).

### Installation

Install the required packages using pip:

```
pip install -Uq upgini catboost
```

### Running the Code

Run the provided Python script to train and evaluate the model:

```
python sales_prediction.py
```

## Description

This code performs the following steps:

1. Data preparation: Downloads the sales dataset, preprocesses it, and splits it into training and testing datasets.
2. Feature enrichment: Utilizes UPGini to enrich features by incorporating additional relevant data sources.
3. Model training: Trains a CatBoost regressor on both the original and enriched datasets.
4. Evaluation: Evaluates the trained models using the Symmetric Mean Absolute Percentage Error (SMAPE) metric.
5. Visualization: Generates a bar chart to visualize sales data over time.

## Results

The results of model evaluation are as follows:

- Error Percentage score of model with the original dataset: 37.65%
- Error Percentage score of model with enriched features: 14.37%

## Dependencies

- Python 3.x
- CatBoost
- UPGini

## Author
Dev Dubal
