# Project Summary
This project is a complete end-to-end data pipeline and predictive analytics system designed to collect, process, and forecast key performance metrics for the *National Basketball Association* (NBA) from 2016 to 2025. It includes modular notebooks for automated data acquisition, parsing, feature engineering, model training, and future prediction.
The pipeline begins with automated data retrieval handled in **get_data.ipynb**, which gathers raw external data from basketball-reference.com and prepares it for downstream processing. The **parse_data.ipynb** notebook converts the raw inputs into structured, validated formats, performing cleaning, transformation, and feature preparation using Pandas Dataframes. These refined datasets are used in **predict.ipynb** where statistical and machine-learning techniques are applied using a RidgeClassifier and Sequential Feature Selector to generate forward-looking predictions and trend insights. In the end, cross-validation is used to evaluate model accuracy.      
The model evaluates to an approximate 64% accuracy in predicting the winner of an NBA game. 

This project was completed in Jupyter Notebook and uploaded to GitHub.

- December 10th, 2025
- Evan Leonard 
