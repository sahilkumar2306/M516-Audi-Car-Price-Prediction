# M516-Audi-Car-Price-Prediction

# Predictive Analysis of Audi Car Prices using Machine Learning

## Module Details
- **Module:** M516 – Business Project in Big Data & AI  
- **University:** Gisma University of Applied Sciences  
- **Student Name:** Sahil Kumar  
- **Student ID:** GH1036801  

## Project Overview
This project offers a machine learning-based solution to the problem of predicting the resale prices of used Audi cars by means of data-driven techniques.  
The main aim of the research is to conduct a study on the impact of the aforementioned major numerical factors like vehicle age, total distance driven, engine size, fuel consumption, and tax on the prices of cars in the resale market.

The project adheres to a well-defined data science pipeline that comprises data preprocessing, exploratory data analysis (EDA), regression modeling, and performance evaluation.

## Business Context
Accurate valuation of second-hand vehicles is very important for everyone involved in automotive business - dealers, resellers, and consumers.  
It can be very difficult to determine the right market value because of factors like depreciation and different mechanical conditions.  
The project here shows the use of regression models based on machine learning to aid pricing decisions driven by historical data.

## Dataset
- **Dataset File:** `audi.csv`

The dataset of used Audi cars comprises listings with these features: 
- Model 
- Year 
- Price (target variable) 
- Transmission 
- Mileage 
- Fuel Type 
- Tax 
- MPG 
- Engine Size 

It is a dataset for preprocessing, analysis, visualization, and predictive modeling.

## Methodology

### Data Preprocessing
- Duplicate entries have been removed. 
- Records with price values that are either missing or zero have been removed. 
- mileage values exceeding 300,000 miles have been filtered out. 
- Numerical data types were made consistent.

### Exploratory Data Analysis
- Histogram analysis for price distribution 
- Scatter plots for the relationship between price and both mileage and engine size 
- Correlation heatmap for numerical factors

### Model Development
- Chosen numerical attributes:
  - Year
  - Mileage
  - Engine Size
  - MPG
  - Tax
- Division of data into training set (80%) and test set (20%)
- A Linear Regression model was utilized for price forecasting.

### Model Evaluation
The model's performance assessment was conducted through the application of the following metrics:
- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R² Score

## Results
- The vehicle's year and engine size were highly positively correlated with price.
- Mileage, on the other hand, was strongly negatively correlated with price, thus confirming the depreciation effects.
- The Linear Regression model produced an R² score of around 0.76, which is a sign of good explanatory power.

## Challenges and Limitations
- Categorical variables (e.g., model name, fuel type) were omitted because of their inconsistent formatting.
- Outlier presence necessitated filtering to ensure model stability.
- Linear Regression might not be able to reflect complicated non-linear relationships.

## Conclusion and Future Work
The project illustrates the use of regression-based machine learning models in accurately estimating the prices of second-hand Audi cars based on quantitative features.  
Future enhancements will probably involve:
- Encoding of categorical variables
- Use of sophisticated models like Random Forest or Gradient Boosting
- Creation of a pricing application for deployment

## GitHub Repository Link
🔗 https://github.com/sahilkumar2306/M516-Audi-Car-Price-Prediction

## Video Link
🎥 https://youtu.be/gyj_HVmJc6k