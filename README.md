# mis-data-challenge
Submission for MIS data challenge

Includes Orange 3 workflow file, dataset, and data dictionary needed to interpret the model explanations.

CatBoost and XGBoost versions used were

Orange version used was 3.31.0 with the explain add-on (version 0.4.2).  Recommend either pausing or unchecking
automatic functions.  Given the size of the dataset and need to calculate shapley values/feature importances,
a small tweak can lead to Orange trying to re-run everything, which may freeze/crash the program depending 
on your hardware.  Typically, it will recover after some time.

