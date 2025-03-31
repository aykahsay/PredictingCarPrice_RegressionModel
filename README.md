# Project Overview

This repository contains files related to a **Linear Regression** model built using the [`imports-85`](imports-85.data) dataset. The project aims to **predict the price of automobiles based on their important features** such as the number of cylinders, horsepower, and other specifications.

## Files Description

- [**`LineaRegression.ipynb`**](LineaRegression.ipynb): Jupyter Notebook implementing a **Linear Regression** model for predicting automobile prices based on key features.
- [**`imports-85.data`**](imports-85.data): The main dataset containing automobile specifications such as the number of cylinders, horsepower, and other features.
- [**`imports-85.names`**](imports-85.names): Metadata file providing column descriptions for `imports-85.data`.
- [**`misc/`**](misc/): Contains additional scripts and resources related to **data preprocessing, visualization, and model evaluation**.
- [**`README.md`**](README.md): This file, explaining the contents and purpose of the repository.

## Usage

1. Load the dataset from [**`imports-85.data`**](imports-85.data).
2. Use [**`LineaRegression.ipynb`**](LineaRegression.ipynb) to preprocess, train, and evaluate the model.
3. Explore [**`misc/`**](misc/) for additional insights and supporting scripts.

If you want to see the model using **LinearRegression**, just replace `Ridge` with `LinearRegression` in the code.



Target

    Target: Predicted car price

Methodology

    Data Preprocessing

        Handle missing values

        One-hot encoding for categorical features

        Analyze low & high cardinality

    Multicollinearity Handling

        Use Variance Inflation Factor (VIF)

        Reduce dimensionality with PCA & heatmaps

    Modeling

        Applied Ridge Regression for regularization

        Evaluated performance using error metrics

Key Insights

    Convertible body style, rear engine location, and specific fuel systems increase price

    Wagon body style tends to lower price

    PCA transformation improved model efficiency

Tools & Libraries

    Python (pandas, numpy, seaborn, matplotlib)

    scikit-learn (regression models, PCA, VIF analysis)

How to Run

    Install dependencies:

pip install pandas numpy seaborn matplotlib scikit-learn

Run the model script:

    python [LinearRegression.ipynb](./path/to/your/scripts/LinearRegression.ipynb)
Feel free to contribute or raise issues for further improvements! 🚀

