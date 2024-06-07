Sowing Success: How Machine Learning Helps Farmers Select the Best Crops

Overview:
This project uses machine learning to help farmers choose the best crop based on soil metrics. We predict crop types using soil data and identify the most important predictive feature.

Dataset:
soil_measures.csv contains:
N: Nitrogen content
P: Phosphorous content
K: Potassium content
pH: Soil pH value
crop: Optimal crop type (target)

Libraries:
pandas
scikit-learn

Workflow:
Load and inspect data.
Split data into training and testing sets.
Evaluate features using Logistic Regression and calculate F1 scores.
Identify the best predictive feature.

Results:
The best predictive feature for crop selection is identified and outputted.
