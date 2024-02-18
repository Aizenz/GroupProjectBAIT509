# GroupProjectBAIT509

Hi there, this is the group project of UBC MBAN 2024' BAIT509

# File Structure

- ---code/: Class proviede test script
- ---df.csv: essential database
- ---main_analysis.ipynb: main analysis jupyter notebook
- ---myenv.yml: conda env file
- ---sql.ipynb: script for building sql server

---

# Things for reproduction

1. Using the following command to build the required Python environment:
   `conda env create -f myenv.yml`
2. Read the truncated database through `df.csv` in `main_test.ipynb`
3. Wait for the resuilt, it will take around 5 minutes based on M1 Pro Macbook, time may variate.

# About the  SQL database

Because `ID` is a reserved variable in postgresql, it will be automately wraped with a quote which will cause problem when querying it. So besure to wrap any columns with `ID` as `"ID"` before quering it. And the quote is case sensitive so besure to type correct.

To avoid merge confict, naming the local file as: localtest_*

for instance:

`localtest_mine.ipynb`

this file will be ignored when pull requiest
