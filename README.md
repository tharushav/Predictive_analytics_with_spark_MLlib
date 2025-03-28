# Predictive Analytics with Spark MLlib

This project demonstrates how to use Apache Spark's MLlib for predictive analytics on the Adult Income dataset.

## Overview

This notebook explores various machine learning models to predict whether a person earns more than $50K per year based on census data.

### Models Implemented:
- Random Forest
- Logistic Regression
- Gradient Boosting
- Linear SVM

## Setup

1. Install dependencies:
```bash
pip install pyspark pandas
```

2. Run the Jupyter notebook:
```bash
jupyter notebook Predictive_analytics_with_spark_MLlib.ipynb
```

## Dataset

The project uses the Adult Income dataset which contains demographic information and predicts whether income exceeds $50K/yr.

## Results

Model performance comparison:
- Random Forest: Best accuracy and F1 score
- Gradient Boosting: Strong performance
- Logistic Regression and Linear SVM: Competitive baseline models
