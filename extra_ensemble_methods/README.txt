These examples on XGBoost will be continued on a later lecture.

Quick notes:

Both XGBoost (classification/regression) seem to be very unstable
with subsequent training runs. 

Ideas to try:
- lock down the random seed
- use an optimization framework to find optimal parameters, maybe even Optuna

Other notes:

- Heart disease classification with SVM => this is a sweet spot for SVM, a small
and limited medical dataset => extremely common use case for SVM, so it's expected
SVM shines with this dataset
    - This explains why SVM seems like a better solution for this dataset than XGBoost
    initially, but we'll see what happens after we optimize the XGBoost parameters a bit more