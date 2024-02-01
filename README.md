# GroupProjectBAIT509

Hi there, this is the group project of UBC MBAN 2024' BAIT509

# About the database

Because `ID` is a reserved variable in postgresql, it will be automately wraped with a quote which will cause problem when querying it. So besure to wrap any columns with `ID` as `"ID"` before quering it. And the quote is case sensitive so besure to type correct.

To avoid merge confict, naming the local file as: localtest_*

for instance:

`localtest_mine.ipynb`

this file will be ignored when pull requiest
