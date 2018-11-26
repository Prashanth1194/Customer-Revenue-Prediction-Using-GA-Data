Data:

train-flattened - Google Analytics transaction level data of Google Merchandise Stor

Models:

phase1_glm.sav - Logistic Regression model from Phase 1
phase1_rf.sav - Random Forest Classifier model from Phase 1
phase1_gbm.sav - Gradient Boosting Classifier model from Phase 1
phase2_lm.sav - Linear Regression model from Phase 2
phase2_rf.sav - Random Forest Regressor model from Phase 2
phase2_gbm.sav - Gradient Boosting Regressor model from Phase 2
bgf.pkl - Betagofitter model from Phase 3

Libraries to be installed (Apart from pre-installed packages such as pandas,numpy,sklearn,matplotlib,pickle,datetime and warnings):

pip install -U imbalanced-learn
pip install lifetimes
pip install seaborn


Note: Keep all the data files, code and the model files in the same location
