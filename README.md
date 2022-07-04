# Diabete-Classification
A data mining project for detecting Diabetic patients based on a databased gathered from kaggle.
it contains the following steps:
- **preprocess**  
  + handle null and unknown values
  + remove whitespaces form dataset
  + one-hot encode
  + scaling
- **Train**  
  train a xgboost classifier on the dataset
- **Fine-Tune**  
  fine tune the model with grid search for findinf the optimal hyperparameters
- **Evaluate the best model**
