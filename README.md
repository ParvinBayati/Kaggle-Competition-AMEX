# Machine Learning Projects: Kaggle Competition AMEX

Link to the problem discribtion: https://www.kaggle.com/competitions/amex-default-prediction


American Express, as the world's largest payment card issuer, aims to leverage machine learning to predict credit default more effectively. Participants will work with an extensive dataset containing time-series behavioral data and anonymized customer profiles. The goal is to develop a superior machine learning model that surpasses the current production model.

ataset Description
The objective of this competition is to predict the probability that a customer does not pay back their credit card balance amount in the future based on their monthly customer profile. The target binary variable is calculated by observing 18 months performance window after the latest credit card statement, and if the customer does not pay due amount in 120 days after their latest statement date it is considered a default event.

The dataset contains aggregated profile features for each customer at each statement date. Features are anonymized and normalized, and fall into the following general categories:

D_* = Delinquency variables
S_* = Spend variables
P_* = Payment variables
B_* = Balance variables
R_* = Risk variables
