## Data-Driven Insights into Seattle Airbnb Pricing

This project, titled "Seattle Airbnb Price Prediction and Analysis," involves the comprehensive analysis and modeling of Airbnb data in Seattle. The codebase is  documented and organized into several key stages:

Data Cleaning:
The initial phase of the project focuses on data cleaning and preprocessing. It includes importing essential libraries, reading data from CSV files ('calendar.csv' and 'listings.csv'), and performing various data transformations. These transformations include handling date formats, converting binary indicators, creating additional date-related columns, and addressing missing values. Categorical columns are converted into dummy variables, and appropriate data normalization is applied.

Exploratory Data Analysis (EDA):
The EDA section encompasses the exploration of data statistics, such as summary statistics, data types, and null values. It delves into the property-specific analysis by determining the maximum number of available listings for each property type. It calculates summary statistics for property-specific listing availability. Additionally, EDA involves visualization through histograms, scatter plots, and various charts, providing insights into the dataset's characteristics and trends.

Machine Learning and Statistical Models:
The heart of the project is the creation of predictive models using machine learning and statistical techniques. The dataset is prepared for modeling, with features and target variables defined. The project employs various algorithms, including Random Forest, Gradient Boosting Regressor, K-Nearest Neighbors (KNN) Regressor, and ElasticNetCV, to predict listing prices. Each model is carefully tuned and evaluated using metrics like Mean Squared Error (MSE) and R-squared.

Web Application Development:
The final part of the project involves the creation of a user-friendly web application using Flask. Users can input details about an Airbnb listing, and the application provides a price prediction based on the chosen features. The application leverages a trained Random Forest model to make predictions.

This project aims to assist both renters and hosts in making informed decisions related to Airbnb listings in Seattle. Users can estimate the price of listings, and hosts can optimize their pricing strategies. The codebase is well-documented and provides a detailed understanding of the entire workflow, from data cleaning to web application development, making it accessible and informative for other data enthusiasts.





