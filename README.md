# MIS Data Challenge Submisison
Submission for MIS data challenge

Includes Orange 3 workflow file and data dictionary needed to interpret the model explanations.

Dataset was too large to upload, but can be found here:
[ASCII Version](https://www.cdc.gov/brfss/annual_data/2020/files/LLCP2020ASC.zip)
[SAS .XPT Version](https://www.cdc.gov/brfss/annual_data/2020/files/LLCP2020XPT.zip)


Install CatBoost and XGBoost into your conda environment to utilize in the Gradient Boosted
Forest Model widget.

Orange version used was 3.31.0 with the explain add-on (version 0.4.2).  Recommend either pausing or unchecking
automatic functions.  Given the size of the dataset and need to calculate shapley values/feature importances,
a small tweak can lead to Orange trying to re-run everything, which may freeze/crash the program depending 
on your hardware.  Typically, it will recover after some time.

