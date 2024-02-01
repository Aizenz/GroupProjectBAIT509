# GroupProjectBAIT509

Hi there, this is the group project of UBC MBAN 2024' BAIT509

# About the database

Because `ID` is a reserved variable in postgresql, it will be automately wraped with a quote which will cause problem when querying it. So besure to wrap any columns with `ID` as `"ID"` before quering it. And the quote is case sensitive so besure to type correct.

To avoid merge confict, naming the local file as: localtest_*

for instance:

`localtest_mine.ipynb`

this file will be ignored when pull requiest


# Things we can do list:



* Models we have learnt
* Classification-> Target: Categorical or binary
  * DummyClassifier
  * DecisionTree
  * KNN
  * Naive Bayers -> Text content extraction
  * Logistics Regression
* Prediction-> Target: Numeric, continous
  * DummyPrediction
  * Linear Regression
  * *Non-Linear Regression (Not Covered)*
* Preprocessing:
  * imputering->fillna
  * encode:
    * ordinal
    * one-hot
  * scalaring-> for SVM like model
  * standarlizing-> for SVM like model
  * column transformation
  * make_pipline
* Hyperparameter Optimazation
  * validation check
  * grid/random search
* Final:
  * data visualization:
    * descriptive analysis
    * decision boundaries
    * tree map
    * validation/train score
  * report delivery
