![Alt_Text](https://github.com/KevinNourian/Insurance/blob/main/Images/air-2640661_640.png)
# Introduction
Travel insurance is a type of insurance policy that provides coverage for a range of unexpected events that can occur during a trip, such as medical emergencies, trip cancellations or interruptions, lost or stolen luggage, and other mishaps that can result in financial loss. Travel insurance can help travelers feel more secure and protected while traveling by providing financial compensation for unexpected expenses or losses. Depending on the policy, coverage can include medical expenses, emergency evacuation, trip cancellation or interruption, lost or stolen baggage, and other travel-related incidents.

Travel insurance provides benefits to travelers by giving them peace of mind and protection against unexpected events that may occur while traveling. By promoting the benefits of travel insurance, insurers can encourage travelers to purchase policies and reduce their financial risk while traveling.

Travel insurance policies can generate significant revenue for insurers by charging premiums based on the level of coverage and the length of the trip. The insurance company assumes the risk of potential losses that the policyholder may incur during their trip, and in exchange, the policyholder pays a premium for that coverage.

# Dataset
In this project, I will analyze the data from nearly 2000 previous customers of an Indian travel insurance company from 2019. The data set contains nine (9) features regarding each customer. The target feature indicates if the customer bought travel insurance. The data set called, "Travel Insurance Prediction Data" is available on Kaggle.

# Goal
The goal of this project is to create a model with an accuracy score of 75% or higher to predict if a future customer will buy travel insurance.

# Technical Requirements
1. Download the data from Travel Insurance Prediction Data.
2. Perform exploratory data analysis. This should include creating statistical summaries and charts, testing for anomalies, checking for correlations and other relations between variables, and other EDA elements.
3. Perform statistical inference. This should include defining the target population, forming multiple statistical hypotheses and constructing confidence intervals, setting the significance levels, conducting z or t-tests for these hypotheses.
4. Apply various machine learning models to predict the TravelInsurance column using the other features. This should include hyperparameter tuning, model ensembling, the analysis of model selection, and other methods.
5. Provide clear explanations in your notebook. Your explanations should inform the reader what you are trying to achieve, what results did you get, and what these results mean.
6. Provide suggestions about how your analysis can be improved.

# Conclusions
**The Analysis of the Data:** I reviewed nearly 2000 data points related to customers of a travel insurance business. <br>
**The Goal of the Project:** The goal of this project was to find a model that could predict if a new customer would buy travel insurance with a high level of accuracy (75% or higher).<br>
**Models:** I utilized several models with varying results.<br>
**Performance of Models:** Some of the models exceeded the 75% accuracy standard. K Nearest (using the default hyperparameters) was able to get better or similar results than any other model, including the more complex ones.<br>  
**Feature Engineering and Hyperparameter Testing:** I tried feature engineering and hyperparameter testing with techniques such as Backward Elimination, SHAP and OPTUNA. OPTUNA showed the best results.<br>
**Stochastic System:** Human behavior is hard to classify and cannot be easily capsulized and predicted. For this reason, obtaining a very high accuracy score (over 80%) may be very difficult to do.<br>
**Business Recommendation:** With accuracy scores of over 80% using some of the models, I recommend utilizing a simple KNN machine learning model to predict if a future customer will purchase travel insurance.<br>
