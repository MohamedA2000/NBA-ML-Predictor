# NBA Data Scraping and Ridge Regression Model

This project involves scraping NBA game data for the past five years and building a Ridge regression model to predict the accuracy of final scores. The model has achieved an accuracy rate of over 63%, making it a valuable tool for predicting NBA game outcomes.

## Table of Contents

- [Project Overview](#project-overview)
- [Data Scraping](#data-scraping)
- [Ridge Regression Model](#ridge-regression-model)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Dependencies](#dependencies)

- [License](#license)

## Project Overview

In this project, we combined web scraping techniques using Playwright and BeautifulSoup to collect comprehensive NBA game data spanning the last five years. This data serves as the foundation for building our predictive model.

The predictive model is based on Ridge regression, a popular linear regression technique used in machine learning. The model has been fine-tuned to provide accurate predictions for NBA game final scores.

## Data Scraping

We used Playwright and BeautifulSoup to scrape NBA game data, including player statistics, team performance, and game outcomes. The data was collected from various sources, ensuring a comprehensive dataset for model training.

## Ridge Regression Model

Our predictive model employs Ridge regression, a linear regression variant known for its ability to handle multicollinearity and overfitting. The model uses historical NBA game data as input features to predict the final scores of future games. With an accuracy rate exceeding 63%, the model is a promising tool for forecasting NBA game outcomes.

## Getting Started

To get started with this project, follow these steps:

1. Clone this repository to your local machine.
2. Install the required dependencies (see [Dependencies](#dependencies)).
3. Follow the usage instructions to run the Ridge regression model on your data.

## Usage

To use the Ridge regression model for predicting NBA game outcomes, follow these steps:

1. Prepare your NBA game data in a suitable format.
2. Load the data into the model.
3. Run the model to obtain predictions.

Here's an example of how to use the model:

```python
# Load the trained Ridge regression model
from sklearn.linear_model import Ridge

model = Ridge()
model.load('ridge_regression_model.pkl')

# Prepare input features (game data)
input_data = ...

# Make predictions
predictions = model.predict(input_data)
```

## Dependencies
This project relies on the following Python libraries and packages:

Playwright: For web scraping NBA game data.
BeautifulSoup: For parsing and extracting data from web pages.
scikit-learn: For implementing the Ridge regression model.
pandas: For data manipulation.
numpy: For numerical operations.
Install these dependencies using pip:

```
pip install playwright beautifulsoup4 scikit-learn pandas numpy
```
