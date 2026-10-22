
# Machine Learning Datasets

This folder contains datasets used in the Machine Learning experiments in this repository.

## Datasets

| Dataset | Experiment |
|---|---|
| Iris Dataset | SVM, Decision Tree and KNN Classification |
| Titanic Dataset | Data Exploration and Visualization |
| Diabetes Dataset | Diabetes Prediction using Logistic Regression |
| House Price Dataset | House Price Prediction using Linear Regression |
| Employee Dataset | Employee Data Preprocessing |
| Customer Dataset | Customer Segmentation using K-Means |

## Dataset Sources

Datasets may be loaded from Python libraries or external sources, or stored locally as CSV files.

Only datasets actually used by the notebooks will be added here. Dataset sources and file names will be documented after checking each experiment.

## Usage

Load a CSV dataset in Python using Pandas:

```python
import pandas as pd

df = pd.read_csv("your_dataset.csv")
print(df.head())
```
