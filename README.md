# goldornogold

## Table of contents
* [General info](#general-info)
* [Features](#features)
* [Process](#process)
* [Stack](#stack)
* [Conclusion](#conclusion)

## General info
Gold industry is in desperate need of a person that can verify that gold production is producing enough gold
## Features
Tooo many features, they differ in stages. Many of them aren't needed in the models
## Process
|Stage | Description|
|--------|--------|
|First stage| Data preprocessing: removing Nans and giving data a good (and right) look|
|Second stage|Work with unit concentration,distribution and overall concentration  in different stages|
|Third stage| Smape model and calculations|
|Fourth stage| Trained and chose the best model for rougher_output|
## Stack
Project is created with:
* Pandas
* Numpy
* Sklearn
  1. Sklearn.preprocessing
    1. StandardScaler
    2. OneHotEnocder
  2. Model_selection.train_test_split
  3. sklearn.linear_model.LinearRegression
  4. sklearn.ensemble.RandomForestClassifier
  5. sklaern.tree.DecisionTreeClassifier
  6. DummyRegressor
  7. AdaBoost and GradientBoost
  8. sklearn.metrics.mean_absolute_error	
## Conclusion
* Concentrations of metals turned out to be normal on every stage
* The best model for deductiong final.output.recovery is GradBoost
* Even performed Dummy-test to test whether it even makes sense

