# Airbnb Price Prediction in New York City

This project aims to predict Airbnb listing prices in New York City using a regression model. The dataset consists of various features such as room type, location (neighborhood), and the number of reviews. The project follows a standard data science workflow, including data exploration, preprocessing, feature engineering, and model training and evaluation.

## Project Overview
Accurately predicting Airbnb prices is essential for hosts and guests alike, ensuring fair pricing and informed decision-making. This project leverages machine learning techniques to predict the prices of listings based on available features in the dataset.

### Key Steps:
1. **Data Preprocessing**:
   - Missing values were handled for important features like `reviews_per_month` and `last_review`.
   - Outliers were detected and removed to ensure the model's robustness.
2. **Exploratory Data Analysis (EDA)**:
   - Visualized the relationships between room type, neighborhood, and price.
   - Explored price variations based on room type and neighborhood group.
3. **Modeling**:
   - The data was split into training and testing sets.
   - A linear regression model was built to predict listing prices.
   - The model was evaluated using metrics such as Root Mean Squared Error (RMSE) and R-squared.
4. **Cross-Validation**:
   - Cross-validation was used to assess the performance of the model.
   - Both RMSE and R-squared were used to evaluate the accuracy and fit of the model.

### Results:
- The linear regression model achieved an R-squared of 0.56 on the test data, explaining approximately 56% of the variance in prices.
- RMSE for the model was 38.6, indicating the average difference between the predicted and actual prices.

## Libraries Used:
- `tidymodels`
- `dplyr`
- `ggplot2`
- `broom`
- `GGally`

## How to Use:
1. Clone the repository:  
   ```bash
   git clone https://github.com/yourusername/airbnb-price-prediction-nyc.git
