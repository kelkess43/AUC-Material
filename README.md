# AUC Material

Here are the links to open the notebooks directly in Google Colab:

- [Session 1 Notebook](https://colab.research.google.com/github/kelkess43/AUC-Material/blob/main/session%201/session1.ipynb)

---

## Reading CSV Files from GitHub

You can load datasets directly from this repository into your Colab notebook using **pandas** and the raw GitHub link.

### Example

import pandas as pd

url = "https://raw.githubusercontent.com/kelkess43/AUC-Material/main/session%201/data.csv"
df = pd.read_csv(url)

print(df.head())

How to Get the Correct CSV URL
Follow these steps to get the correct link for your dataset:
  1. Go to the CSV file in this GitHub repository.  
  2. Click on the file name to open it.  
  3. In the file view, click the **"Raw"** button (top right).  
  4. Copy the URL from your browser — it will look like this: https://raw.githubusercontent.com/<username>/<repo>/main/<path-to-your-file>.csv
