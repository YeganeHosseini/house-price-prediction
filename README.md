# House Price Prediction Project

## Overview

This project aims to predict house prices using various regression models based on the California Housing dataset. The project involves data exploration, preprocessing, model training, evaluation, and hyperparameter tuning to improve model performance.

## Project Structure

- **Data Exploration and Visualization**: Understanding the dataset through descriptive statistics and visualizations.
- **Output Analysis**: Analysis of the distribution of house prices and correlation between features.
- **Model Training and Evaluation**: Training different machine learning models and evaluating their performance.
- **Hyperparameter Tuning**: Improving model performance using Grid Search Cross-Validation.
- **Advanced Models**: Exploring more complex models like Ridge, Lasso, and Random Forest regression.

## Dataset

The dataset used in this project is the California Housing dataset, which contains information about various features of houses in California, such as median income, house age, and average number of rooms, among others. The target variable is the house price.

## Key Steps

### 1. Data Exploration and Visualization

- **Descriptive Statistics**: Generated statistics to understand the distribution of features.
- **Price Distribution**: Visualized the distribution of house prices using a histogram and Kernel Density Estimate (KDE) curve.
- **Correlation Matrix**: Created a heatmap to visualize the correlation between different features and the target variable (PRICE).

### 2. Output Analysis

- **Heatmap**: Identified strong correlations between features like `MedInc` (median income) and house prices.
- **Detailed Analysis**: Provided insights into mean values, standard deviations, and percentiles for each feature.
- **Correlation Analysis**: Highlighted features with high positive or negative correlations with the target variable.

### 3. Preprocessing the Data

- **Feature Scaling**: Applied StandardScaler to standardize features.
- **Data Splitting**: Split the dataset into training (70%) and testing (30%) sets to evaluate model performance.

### 4. Model Training

- **Linear Regression**: Trained a simple linear regression model to predict house prices.
- **Model Evaluation**: Evaluated the model using Mean Squared Error (MSE) and R-squared (R²) score.

### 5. Hyperparameter Tuning

- **Grid Search Cross-Validation**: Tuned hyperparameters for linear regression using Grid Search CV to improve model performance.
- **Pipeline Implementation**: Used a pipeline to streamline the process of scaling features and applying regression.

### 6. Exploring More Advanced Models

- **Ridge Regression**: Included regularization to prevent overfitting.
- **Lasso Regression**: Performed feature selection by penalizing the absolute size of coefficients.
- **Random Forest Regression**: Utilized an ensemble method to capture non-linear relationships.

### 7. Model Comparison

- **Initial vs Tuned Model**: Compared the performance of the initial linear regression model with the tuned model.
- **Advanced Models Comparison**: Evaluated the performance of Ridge, Lasso, and Random Forest models.

## Results

- **Best Model**: The Random Forest model outperformed other models with the lowest Mean Squared Error (MSE) and highest R-squared (R²) score.
- **Model Insights**: The correlation analysis revealed that `MedInc` is the most significant predictor of house prices.

## Conclusion

The project successfully demonstrated the process of building and evaluating different regression models for house price prediction. The Random Forest model was identified as the best performer, but depending on the needs (e.g., simplicity, feature selection), Ridge or Lasso regression could also be viable alternatives.

## How to Use

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/YeganeHosseini/house-price-prediction.git
   cd house-price-prediction
   ```

2. **Install Dependencies**:

	```bash
	pip install -r requirements.txt
	```


3. **Run the Notebook**:

	Open the Jupyter Notebook and run the cells to execute the code and visualize the results.

## License

This project is licensed under the MIT License.
