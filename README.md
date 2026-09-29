# Regression: House Price Prediction

A machine learning project that predicts house prices using regression models. The full workflow, from data exploration to model evaluation, is implemented in a Jupyter notebook.

## Repository Structure

```
Regression-House-Price-Prediction-/
├── Regression_House_Price_Prediction_.ipynb   # Data preparation, training, evaluation
├── index.html                                  # Project web page
└── README.md                                   # Project documentation
```

## Problem Statement

Given a set of house attributes (such as size, rooms, and location), predict the sale price as a continuous value. This is a supervised regression task.

## Workflow

1. **Load the dataset** and inspect its structure
2. **Exploratory data analysis**: distributions, correlations, and outliers
3. **Preprocessing**: handle missing values, encode categorical features, scale numerical features
4. **Split the data** into training and test sets
5. **Train regression models** and compare their performance
6. **Evaluate** with MAE, MSE, RMSE, and R² score
7. **Visualize** actual versus predicted prices

## Evaluation Metrics

| Metric | Description                                         |
| ------ | --------------------------------------------------- |
| MAE    | Mean absolute error between predicted and true price |
| MSE    | Mean squared error                                  |
| RMSE   | Square root of MSE, in the same units as price      |
| R²     | Proportion of price variance explained by the model |

## Requirements

- Python 3.9+
- Jupyter Notebook / JupyterLab, or Google Colab
- `numpy`, `pandas`, `matplotlib`, `seaborn`, `scikit-learn`

```bash
pip install numpy pandas matplotlib seaborn scikit-learn jupyter
```

## Getting Started

**Run locally**

```bash
git clone https://github.com/TimBroAhm/Regression-House-Price-Prediction-.git
cd Regression-House-Price-Prediction-
jupyter notebook Regression_House_Price_Prediction_.ipynb
```

**Run in Google Colab**

1. Open [colab.research.google.com](https://colab.research.google.com).
2. Choose **File → Open notebook → GitHub** and paste the repository URL.
3. Select `Regression_House_Price_Prediction_.ipynb` and run all cells (**Runtime → Run all**).

## Author

**TimBro**
GitHub: [@TimBroAhm](https://github.com/TimBroAhm)
