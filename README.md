# IFT6390_Weather-Events-Classification_Kaggle-Data-Challenge-1_2021
The submission contains 3 .ipynb notebooks.

These submissions are a part of larger repository of notebooks @ https://github.com/Etrama/IFT6390_Weather-Events-Classification_Kaggle-Data-Challenge-1_2021

The 3 notebooks are:
1. Logistic_Regression_Attempt1.ipynb - This contains the Logistic Regression Code for the 6390 Kaggle Challenge with some hyperparamter tuning.
2. Final_Sub_RF_SMOTE_without_dups.ipynb - This is one of the 2 final submissions to Kaggle, which works on synthetic data without duplicates present in the original data.
3. Final_Sub_RF_SMOTE_Tomek_with_dups.ipynb - This is the one of the 2 final submissions to Kaggle, which works on synthetic data with duplicates.

To run the Logistic_Regression_Attempt1.ipynb notebook:
We need the notebook to be run in a folder which contains a folder called /ift3395-6390-weatherevents/ which has the train and test csvs within it. The rest of the notebook is pretty self-contained and we should be able to run the .ipynb cells line by line.

To run the Final_Sub_RF_SMOTE_without_dups.ipynb
For this notebook we need the data to be in the same folder as above i.e. /ift3395-6390-weatherevents/ which has the train and test csvs within it. The rest of the notebook is pretty self-contained and we should be able to run the .ipynb cells line by line.

To run the Final_Sub_RF_SMOTE_Tomek_with_dups.ipynb:
For this notebook we need the data to be in the same folder as above i.e. /ift3395-6390-weatherevents/ which has the train and test csvs within it. The rest of the notebook is pretty self-contained and we should be able to run the .ipynb cells line by line.

These are not included in the Gradescope submission BUT they are avaialble on Github: https://github.com/Etrama/IFT6390_Weather-Events-Classification_Kaggle-Data-Challenge-1_2021

For the other notebooks:
The data files are generated using the following notebooks:
Feature_Engineering_and_Sampling.ipynb - This will generate ADASYN data and also generate data using other SMOTE techniques with extra features that we tried to engineer. It will generate the data mentioned below:
Entire data with train test split
X_test_std.csv
X_train_ada_std.csv
X_train_std.csv

y_test.csv
y_train_ada.csv
y_train.csv

FeaEngg_Sampling_without_dups_without_extra_features.ipynb - 
Entire data without train test split
X_train_full_ada_std.csv 
y_train_full_ada.cs

X_train_full_std.csv
y_train_full.csv



Based on the flavour of data we want to generate, we can also use:
FeaEngg_Sampling_with_dups_without_extra_features.ipynb - This will generate ADASYN retaining the duplicate data in the original data provided, similar to the notebook mentioned above.



