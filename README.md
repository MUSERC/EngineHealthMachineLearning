# EngineHealthMachineLearning
The expiatory data analysis on engine dataset tried to feature engineering but it seems like there is omitted variables because the accuracy isn't increasing

datasetlink : https://www.kaggle.com/datasets/parvmodi/automotive-vehicles-engine-health-dataset/code?datasetId=3092910&sortBy=dateCreated

Results: 

| Model                      | Test Accuracy |
|----------------------------|---------------|
| Neural Network (30 neurons)| 0.6633        |
| Polynomial Logistic (deg 2)| 0.6556        |
| KNN (k=19)                | 0.6438        |
| Decision Tree (depth=7)   | 0.6397        |
| XGBoost                   | 0.6372        |
| Random Forest             | 0.6366        |
