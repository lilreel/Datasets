# How To Import Datasets to Your Notebook
1. Click the dataset folder.
2. Click the dataset.
3. Click 'Raw'.
4. Copy the URL.
5. You can use the URL.

for e.g:

import pandas as pd
<br>
url : 'https://raw.githubusercontent.com/lilreel/Datasets/main/Telco%20Customer%20Churn/telco_customer_churn.csv'
<br>
df = pd.read_csv(url)
