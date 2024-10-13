# SDoH_Diabetes
Predicting and Understanding the Causal Impact of SDoH and Clinical Factors on Diabetes Status  

Research Question: How can we predict diabetes status (diabetes, pre-diabetes, no diabetes) using demographic, clinical, and Social Determinants of Health (SDoH) data, and what are the causal relationships between these factors and the onset of diabetes?

# Python Environment Setup:
To install the required libraries, we use the requirements.txt file. 
``` bash
conda create -n causal_ai python=3.10 -y
conda activate causal_ai
pip install -r requirements.txt
```

# Data Source:
CDC Diabetes Health Indicators
The Diabetes Health Indicators Dataset contains healthcare statistics and lifestyle survey information about people in general along with their diagnosis of diabetes. The 21 features consist of some demographics, lab test results, and answers to survey questions for each patient. The target variable for classification is whether a patient has diabetes or healthy.

https://archive.ics.uci.edu/dataset/891/cdc+diabetes+health+indicators

# To download the data:
Run the `notebooks/0.0_data_collection.ipynb`, this will download the dataset into the `data` folder.