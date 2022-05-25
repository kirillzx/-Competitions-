# ITMO Hack FinTech Case 2022

The task was to predict the activity of companies by their transactional activity. Its multi-label classification.
### File desriptions
TrainModel.ipynb - file for training model (the paths are prescribed for training on kaggle)

### Model
To solve the problem was choosen XGBClassifier. Its boosting algorithm on trees. With simple Grid Search was found optimal parameters for max depth of the trees and number of trees.
Parameters|Values
---|---
max_depth|8
n_estimators|5000
