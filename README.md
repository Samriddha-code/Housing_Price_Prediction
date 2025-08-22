Housing Price Prediction Using Linear Regression and Recursive Feature Elimination (RFE)

Project Overview
This project focuses on predicting housing prices based on various features of residential properties. The main objective is to build a predictive regression model that reliably estimates house prices using the most relevant features.

Dataset Description
The dataset ("Housing.csv") contains 545 records and 13 columns:
- price: Target variable, price of the house.
- area: Size of the house in square feet.
- bedrooms: Number of bedrooms.
- bathrooms: Number of bathrooms.
- stories: Number of floors/stories.
- mainroad: Whether the house is adjacent to the main road (yes/no).
- guestroom: Presence of guest room (yes/no).
- basement: Presence of basement (yes/no).
- hotwaterheating: Availability of hot water heating system (yes/no).
- airconditioning: Availability of air conditioning (yes/no).
- parking: Number of parking spaces.
- prefarea: Whether the house is located in the preferred area (yes/no).
- furnishingstatus: Furnishing status of the house (furnished, semi-furnished, unfurnished).

Methodology
- Data loading and initial exploration.
- Data preprocessing including encoding categorical variables.
- Feature engineering to create additional meaningful features.
- Splitting data into training and test sets.
- Using Recursive Feature Elimination (RFE) with Linear Regression to select the most important features.
- Training a Linear Regression model with selected features.
- Evaluating the model on test data using mean squared error (MSE), root mean squared error (RMSE), and R-squared metrics.
- Visualizing residuals to assess model fit.

Results
The model provides a statistical relationship between house prices and selected features. Performance metrics and residual analysis indicate the quality and reliability of the predictive model.

Usage
- Load the dataset.
- Run preprocessing and feature selection steps.
- Train the regression model.
- Use the model for prediction on new data.

Tools and Libraries
- Python 3.x
- pandas, numpy for data manipulation
- matplotlib, seaborn for data visualization
- scikit-learn for modeling, feature selection, and evaluation

---
