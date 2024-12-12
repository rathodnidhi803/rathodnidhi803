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
- 👋 Hi, I’m @rathodnidhi803
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

<!---
rathodnidhi803/rathodnidhi803 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
