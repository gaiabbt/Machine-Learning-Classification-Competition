# Supervised Classification (Coursework)

University coursework (MSc Econometrics / Machine Learning). This assignment builds and compares supervised classifiers on a structured prediction dataset and produces out-of-sample label predictions.

## What I did
- Trained baseline models:
  - Linear SVM (LinearSVC)
  - Shallow neural network (Keras)
  - AdaBoost classifier
- Tuned hyperparameters with cross-validation (GridSearchCV / StratifiedKFold)
- Evaluated and compared models using accuracy, balanced accuracy, and F1
- Selected an optimized AdaBoost configuration as the final “advanced classifier”
- Exported test-set predictions in the required {-1, 1} label format to CSV
