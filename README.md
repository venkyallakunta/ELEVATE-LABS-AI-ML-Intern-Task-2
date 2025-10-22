# ELEVATE-LABS-AI-ML-Intern-Task-2
# Step-1: Generate summary statistics (mean, median, std, etc.).
# importing all libraries i.e., import numpy as np , import pandas as pd, import seaborn as sns, import matplotlib.pyplot as plt
# load the dataset titanic=pd.read_csv(r' ')
# summary statistics for numerical columns i.e., (titanic.describe())
# Step-2: Create histograms and boxplots for numeric features.
# Histogram(Age)
# It shows how passanger's ages are distributed
# Most passangers are between 20-40 years old.
# The distribution is slightly right-skewed, meaning there are more younger passengers and fewer older ones.
# Boxplot(Fare)
# Display the spread and outlies.
# You can see a very few high values(outliers)-rich passengers who paid much more for luxury cabins.
# Step-3: Use pairplot/correlation matrix for feature relationships.
# Correlation Matrix: Shows how numerical features relate to each other.
# Pairplot: Visualizes pairwise relationships and distributions.
# Step-4: Identify patterns, trends, or anomalies in the data.
# 1st class passengers survived more frequently.
# Younger passengers had slightly better survival chances. 
# Step-5: Make basic feature-level inferences from visuals
# Passengers with small families had higher chances of survival.
# Very large families faced higher risks due to limited rescue resource
