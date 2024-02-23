# Air Quality Index Prediction Project

## Introduction
This project aims to predict the Air Quality Index (AQI) using historical air quality data collected from various sources through web scraping techniques. Utilizing the Python library Beautiful Soup, we've scraped relevant data from websites that provide air quality information. The project explores several regression techniques to accurately predict the AQI, including Linear Regression, Lasso and Ridge Regression, Decision Trees, and Random Forest Regression.

## Features
- Utilizes historical air quality data for prediction
- Employs various regression techniques for accurate AQI forecasting
- Data collection through web scraping using Beautiful Soup

## Prerequisites
Before you begin, ensure you have met the following requirements:
- Python 3.x
- Libraries: Beautiful Soup, pandas, scikit-learn, numpy

## Installation
To set up the project environment, follow these steps:

```bash
git clone https://github.com/1sharkguy/Airqualityindexprediction.git
cd <project-directory>
pip install -r requirements.txt
```

## Usage
To predict the AQI using the project, follow these steps:

1. Collect the data:
```bash
python scraping.py
```

2. Train the model:
```bash
python 'any_train_model'.py
```

3. Predict the AQI:
```bash
python predict_aqi.py --input <input_data_file>
```

Replace `<input_data_file>` with the path to the data file you want to use for prediction.
