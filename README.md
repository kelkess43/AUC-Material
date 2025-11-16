# AUC Material

Here are the links to open the notebooks directly in Google Colab:

- Session 1 Notebook: https://colab.research.google.com/github/kelkess43/AUC-Material/blob/main/session%201/session1.ipynb

- Session 2 Notebook: https://colab.research.google.com/github/kelkess43/AUC-Material/blob/main/session%202/session2.ipynb

- Session 3 Notebook: https://colab.research.google.com/github/kelkess43/AUC-Material/blob/main/session%203/session3.ipynb

- Session 4 Notebook:https://colab.research.google.com/github/kelkess43/AUC-Material/blob/main/session%204/session4.ipynb
------------------------------------------------------------

## Reading CSV Files from GitHub

You can load datasets directly from this repository into your Colab notebook using pandas and the raw GitHub link.

Example:

import pandas as pd

url = "https://raw.githubusercontent.com/kelkess43/AUC-Material/main/session%201/credit_scoring.csv"
df = pd.read_csv(url)

print(df.head())

------------------------------------------------------------

## How to Get the Correct CSV URL

When you open a file on GitHub, the link you see by default is a "blob" link, for example:

https://github.com/kelkess43/AUC-Material/blob/main/session%201/credit_scoring.csv

This link will not work directly with pandas.read_csv().

To make it work, you need the "raw" link instead, which looks like this:

https://raw.githubusercontent.com/kelkess43/AUC-Material/main/session%201/credit_scoring.csv

Steps to get the raw link:

1. Navigate to the CSV file in this GitHub repository.
2. Click on the file name to open it.
3. In the file view, click the "Raw" button (top right).
4. Copy the URL from your browser — this is the raw link.
5. Use this raw link inside pd.read_csv(...) as shown in the example above.
