Predicting Appliance Energy Consumption in Households

Overview
This project focuses on building a machine learning model to predict household appliance energy consumption using environmental, weather, and time-based data. The aim was to understand factors influencing electricity usage and explore how predictive models can support energy efficiency and cost optimization.

Objectives
The project was designed to predict appliance energy consumption using regression models, identify important factors affecting household energy usage, compare multiple machine learning approaches, and generate insights related to energy optimization and grid management.

Dataset
The dataset contains approximately 19,700 observations recorded at 10-minute intervals. The target variable represents appliance energy consumption measured in watt-hours. Features include indoor environmental sensor readings, outdoor weather conditions, and time-related variables.

Data Preparation
No missing values were present in the dataset. The date column was converted into datetime format, and new time-based features were extracted. Random noise variables were removed to improve model performance, and feature scaling was applied before model training.

Exploratory Data Analysis
Exploratory analysis examined energy consumption distribution, correlations between variables, and usage patterns across different time periods. Visualization helped identify relationships between environmental factors and energy consumption.

Modeling Approach
Several regression models were implemented, including Linear Regression as a baseline model and Random Forest Regressor for improved performance. Hyperparameter tuning was performed using RandomizedSearchCV to optimize the Random Forest model.

Model Evaluation
Models were evaluated using Mean Squared Error and R² score. Train-test comparisons were used to analyze overfitting and generalization performance.

Results
The tuned Random Forest model achieved the best performance with an R² score of approximately 0.56, demonstrating moderate predictive capability for household energy consumption.

Business Relevance
The results show how machine learning can assist in energy optimization, reduction of electricity costs, and improved power grid load planning.

Limitations and Future Work
Energy consumption is influenced by human behavior, making prediction challenging. Future improvements may include lag features, time-series modeling, and advanced algorithms.

Purpose
This project was completed as a practical exercise to strengthen understanding of regression modeling, data preprocessing, and real-world energy prediction problems.
