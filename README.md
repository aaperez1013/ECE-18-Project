# ECE-18-Project
# Predictive Modeling for EV Battery Charging Performance

For the last quarter of my undergrad at UC San Diego, I am taking ECE 18, of which it has a project involving classifcation. This repository contains my Python code and presentation slides.

The following description is literally what I submitted for the proposal (which was a Canvas assignment):

## Proposal
As someone who is taking ECE MAE 148, I have been intrigued by the usage of battery cells in RC drones, and have been conscious of degradation my phone's battery for the last 3-4 years. The interests in these two fields dictated my choice while researching what to do for this project.
Electrical vehicles are becoming the cornerstone of sustainable transportation, but require careful watch with battery health; performance during charging cycles is critical for both consumer satisfaction and power grid stability. Three factors come into play: rapid charging, cycling behavior, and temperature, all of which put thermal and structural stress on Lithium-ion cells. This leads to increased degradation and posses safety risks. As such, this project aims to build a predictive machine learning pipeline to classify optimal charging duration and evaluate battery degradation rates, protecting hardware and optimizing energy efficiency.

## Dataset
On Kaggle, a dataset by the title "EV Battery Charging Data," uploaded by the user Ziya (https://www.kaggle.com/datasets/ziya07/ev-battery-charging-data Links to an external site.) can be found and will be utilized in this project. This following are a few of the features of the dataset: state-of-charge, voltage, current, temperature (battery and ambient), and efficiency. There are more categorical features, such as charging mode and battery type. Due to the amount of features and overall amount of data available, this dataset should be excellent and sufficient for this project.

## Models
The anticipated approach for this model will be using scikit-learn and building a Logistic Regression algorithm as a baseline model, and then compare it to a kNN. Logistic Regression will be useful because it has interpretability and efficiency in classifying, and kNN provides potential non-linear relationships, creating a well-balanced comparison. I plan on using multiclass evaluation metrics due to there being multiple categories to provide accuracy. If coding becomes too complex, then I will switch to binary evaluation metrics (i.e. optimal vs suboptimal results) to simplify.
