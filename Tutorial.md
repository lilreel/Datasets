# How To Import Datasets to Your Notebook
1. Click the database folder you are looking for.
2. Click the dataset.
3. Click 'Raw'.
4. Copy the URL.
5. You can use the URL.

for e.g:

import pandas as pd
url : 'https://raw.githubusercontent.com/lilreel/Datasets/main/Telco%20Customer%20Churn/telco_customer_churn.csv'
df = pd.read_csv(url)
