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

The task is to predict, for each customer_ID, the probability of a future payment default (target = 1).

Note that the negative class has been subsampled for this dataset at 5%, and thus receives a 20x weighting in the scoring metric.

Data Files has been provied in the above link:

train_data.csv - training data with multiple statement dates per customer_ID

train_labels.csv - target label for each customer_ID

test_data.csv - corresponding test data; your objective is to predict the target label for each customer_ID

sample_submission.csv - a sample submission file in the correct format
