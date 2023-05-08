# Energy Prediction Model for House Energy Consumption Optimization

This project aims to predict the energy consumption of household appliances and optimize their energy usage based on the predicted results. The project utilizes machine learning algorithms to analyze and predict the energy usage of different household appliances based on various parameters such as temperature, humidity, and date/time.

## Data Source

The dataset used in this project is sourced from the UCI Machine Learning Repository and can be found at the following link: https://archive.ics.uci.edu/ml/datasets/Appliances+energy+prediction. The dataset contains 19 different parameters related to energy usage, weather conditions, and time, with a total of 19,735 observations.

## Models Used

Several machine learning algorithms were utilized in this project to predict the energy consumption of household appliances. These models include:

- Logistic Regression
- Naïve Bayes
- k-Nearest Neighbors (KNN)
- Bagged Decision Tree
- Random Forest
- Gradient Boosting Classifier (GBC) with hyperparameters
- Multi-Layer Perceptron (MLP)
- Support Vector Machine with Radial Basis Function Kernel (SVM_RBF)
- XGBoost with hyperparameters

## Results

After evaluating the performance of each model, the highest accuracy achieved was 93 percent. The model classifies the home appliances into two classes: less than 60 watts and more than 60 watts, based on the energy consumption prediction. The optimized energy usage can be achieved by implementing the predicted results from the model, allowing households to save energy and reduce their electricity bills.
