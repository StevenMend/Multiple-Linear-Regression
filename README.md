# Multiple Linear Regression

## Project Overview

This project aims to predict housing prices in Boston during the 1970s using multiple linear regression techniques. By analyzing various socioeconomic and physical characteristics, the model provides insights into the factors influencing real estate values in the area.

### Key Objectives

- Analyze the relationship between housing prices and various features.
- Develop a multiple linear regression model for price prediction.
- Evaluate model performance using statistical metrics.

### Contents

- **Data Exploration**: Initial analysis of the dataset to understand variable relationships.
- **Data Preprocessing**: Cleaning and transforming data, handling missing values, and normalization.
- **Model Building**: Implementation of a multiple linear regression model.
- **Residual Analysis**: Assessing the residuals to check for normality and skewness.
- **Out-of-Sample Testing**: Evaluating model performance on unseen data.
- **Prediction**: Estimating housing prices based on average and specific property characteristics.

### Data Insights

- **Significant Variables**: The number of rooms (RM) and air quality (NOX) are major determinants of housing prices. Increased room count correlates with higher prices.
- **Statistical Findings**: The average home price was $22,530 during the 1970s, indicating notable affordability.
- **Visualizations**: Graphs highlight patterns, including housing density near employment centers and proximity to the Charles River.

### Model Evaluation

- The model was assessed using metrics such as R² and Mean Squared Error (MSE). The results show:
  - Original Model Test Data R²: 0.67
  - Log Model Test Data R²: 0.74
- Residuals of the log price model had improved skewness and mean values, indicating a better fit.

### Predictions

Using the model, predictions for property values were made based on average characteristics and specific scenarios, demonstrating the practical applicability of the model in real estate.

### Requirements

- Python 3.x
- Necessary Libraries:
  - pandas
  - numpy
  - scikit-learn
  - matplotlib
  - seaborn

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/StevenMend/Multiple-Linear-Regression.git
