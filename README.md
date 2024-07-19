# Agricultural Yield Prediction

## Project Overview

This project involves the analysis and modeling of agricultural data using various machine learning and statistical techniques. The project follows the KDD (Knowledge Discovery in Databases) process to clean, integrate, select, transform, and analyze the data, with a focus on predicting crop yields based on factors like rainfall, temperature, and pesticide usage.

## Notebooks

### 1. **Dataset Preparation (`dataset.ipynb`)**
- **Data Cleaning**: The dataset includes rainfall, pesticides, temperature, and yield data.
- **Data Integration**: Merging datasets based on `Country` and `Year`.
- **Data Transformation**: Renaming columns, dropping unnecessary columns, and creating the final dataset.
- **Output**: `Data.csv` which is used in further analysis and modeling.

### 2. **Data Visualization (`visualization.ipynb`)**
- **Exploratory Data Analysis (EDA)**: Visualizing data distributions, trends over years, and relationships between variables.
- **Techniques Used**: Bar plots, line plots, scatter plots, and heatmaps using `matplotlib`, `seaborn`, and `plotly`.

### 3. **Modeling (`model.ipynb`)**
- **Data Mining**: Preparing data for modeling through one-hot encoding and feature scaling.
- **Models Implemented**: Linear Regression, Decision Tree, Random Forest, Gradient Boosting, XGBoost, Bagging Regressor, and KNN.
- **Performance Metrics**: Mean Squared Error (MSE), R2 Score, and visualization of actual vs. predicted values.
- **Output**: Model performance results saved in `model_performances.csv`.

### 4. **Novelty Detection (`novalty.ipynb`)**
- **ARIMA**: Time series forecasting to predict future crop yields.
- **LSTM**: Deep learning approach for long-term yield prediction.
- **Evaluation**: Mean Squared Error and visualization of true vs. predicted yields over time.

## Files
- `rainfall.csv`, `pesticides.csv`, `temp.csv`, `yield.csv`: Raw data files.
- `Data.csv`: Cleaned and merged dataset.
- `model_performances.csv`: Performance metrics of different models.

## Usage

- **Data Preparation**: Run `dataset.ipynb` to prepare the dataset.
- **Visualization**: Use `visualization.ipynb` to perform EDA and visualize the data.
- **Modeling**: Train and evaluate models by running `model.ipynb`.
- **Novelty Detection**: Predict future yields using `novalty.ipynb`.

## License

This project is licensed under the MIT License.
