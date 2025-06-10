# Flight Delay Prediction
## Objective - Predict the arrival delay of flights  (arrival delay > 15mins)
## Datasource - Kaggle
## Data cleaning/pre-processing
- Import the trimmed csv file
- Handle the null values
- Change the datatypes
- Convert categorical cloumns to binary using labelencoder
- Define the target variable

## Data visualization
### Perform basic visualization to understand pattterns using seaborn
- Distribution of arrival delays
- Flight cancellation count
- Top 10 Airlines by Flight count
- Average arrival delay by airline
- Heatmap for correlation analysis

## Data processing of ML
- Drop the leakage columns
- Set the X(target variable) and Y(features) variables
- Split the data into test and train

## Model prediction
- Train using XGboost(logloss metric)
- Model prediction on unseen data - accuracy_score, classification_report, confusion_matrix. Accuracy result - 95%
- Cross-validation scores, Mean accuracy, SD
- Generate ROC curve(score = 0.96 - good fit model)
- Plot feature importance graph
 
