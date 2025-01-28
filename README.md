# Weather Trend Forecasting Project

This project analyzes the Global Weather Repository dataset to forecast weather trends using both basic and advanced techniques.

## Project Structure

- `data_loader.py`: Handles data loading, cleaning, and preprocessing
- `exploratory_analysis.py`: Contains EDA functions and visualizations
- `forecasting_models.py`: Implements various forecasting models
- `main.py`: Main script that orchestrates the analysis

## Features

### Basic Assessment
- Data cleaning and preprocessing
- Missing value handling
- Outlier detection and treatment
- Basic EDA with visualizations
- Temperature trend analysis
- Basic forecasting model

### Advanced Assessment
- Multiple forecasting models (Linear Regression, Random Forest, XGBoost)
- Ensemble modeling
- Geographical pattern analysis
- Correlation analysis
- Feature importance analysis

## Requirements

- Python 3.8+
- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn
- xgboost

## Usage

1. Install required packages:
```bash
pip install pandas numpy scikit-learn matplotlib seaborn xgboost
```

2. Place the "Global Weather Repository.csv" file in the project directory

3. Run the analysis:
```bash
python main.py
```

## Results

The analysis includes:
- Visualization of temperature trends
- Correlation analysis of weather parameters
- Geographical weather patterns
- Model performance metrics
- Ensemble predictions

## Model Evaluation

The project evaluates multiple models:
- Linear Regression
- Random Forest
- XGBoost
- Ensemble of all models

Metrics used:
- Mean Squared Error (MSE)
- Mean Absolute Error (MAE)
- R-squared Score# weather-trend-forecasting
Advanced analysis of global weather trends using Python.
