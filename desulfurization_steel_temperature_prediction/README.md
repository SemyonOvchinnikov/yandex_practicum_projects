# Steel temperature prediction during desulfurization

## Description
In order to optimize production costs, the steel plant decided to reduce electricity consumption at the steel processing stage. It is required to build a model that predicts the temperature of the steel. The model will be used to simulate various process scenarios. End users - customer's production technologists

## Plan
1. EDA. Analysis of the data properties, patterns, distributions and anomalies.
2. Data preprocessing. Aggregation of data for data_arc and data_temp. Creation of additional features. Data joining into one dataset with Inner Join method. Removing incorrect values (negative and missing values). Split into training and test samples. Processing of abnormal values in a training sample. Preparation of the features (scaling, etc.)
3. Models selection and pipelines development. Selection of hyperparameter ranges. Training and selection of optimal model with RandomizedSearchCV
4. Testing the model, adequacy check with a constant model, feature importance
5. Report preparation.

## Teck Stack
*pandas, numpy, sklearn, catboost, lightgbm, matplotlib, seaborn*
