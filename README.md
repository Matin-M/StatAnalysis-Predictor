# StockTechPredictor

## Overview
This evaluator is crafted for advanced financial data analysis, incorporating diverse machine learning models such as LSTM, LSTM with sentiment analysis, XG Boost, and Logistic Regression. It specializes in analyzing technical indicators and time series data to forecast market trends and predict asset prices.

### Data Labeling Function
- Includes the `label_data_fixed_days` function for labeling data based on a specified number of days (`d`).
- Supports binary or bipolar labeling, integral for supervised learning models.

### Model Training and Evaluation
- Uses time series split for data validation, ensuring chronological accuracy.
- Performance evaluated using accuracy metrics and classification reports.

### Feature Selection Strategy
- Implements SelectKBest with `mutual_info_classif` to optimize model efficiency.
- Prioritizes the most influential indicators for predictive analysis.

### Parameter Optimization
- Allows adjustment of the `d` parameter to assess its impact on model accuracy.
- Enables tailored optimization for specific forecasting objectives.

### Result Visualization
- Includes capabilities to graphically depict model performance trends.
- Visualizes accuracy variations against different `d` values.
