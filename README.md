# Wine-Quality-Prediction
In this project, a model for wine quality prediction was developed. Necessary libraries where imported. The dataset contained 1143 rows and 13 columns. It was observed that they were no missing values and duplicated values in the dataset. The ID column was dropped because it wasn't necessary in the analysis.

Exploratory data analysis was done on the dataset. In correlation matrix, it was observed that alcohol is most correlated to quality. Data preprocessing was done after which the models were built.

Linear regression was used to analyze it was discovered that the model performed very poor (23.4%). Random forest classifier and Xgb classifier was then used.

The accuracy for random forest classifier was 91.2% and Xgb classifier was 93%.
