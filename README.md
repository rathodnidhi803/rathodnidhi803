import pandas as pd

# Create a list of datasets and their categories
data = [
    {"Category": "Supervised Learning", "Dataset Name": "Iris Dataset", "Task Type": "Classification", "Description": "Classifies species of Iris flowers.", "Source": "UCI"},
    {"Category": "Unsupervised Learning", "Dataset Name": "Mall Customer Dataset", "Task Type": "Clustering", "Description": "Clusters customers based on income and spending.", "Source": "Kaggle"},
    {"Category": "NLP", "Dataset Name": "Sentiment140", "Task Type": "Sentiment Analysis", "Description": "Sentiment analysis from Twitter.", "Source": "Kaggle"},
    {"Category": "Time Series", "Dataset Name": "Airline Passengers", "Task Type": "Forecasting", "Description": "Monthly number of airline passengers.", "Source": "UCI"}
]

# Convert list to DataFrame
df = pd.DataFrame(data)

# Save to Excel file
df.to_excel("Machine_Learning_Datasets.xlsx", index=False)


