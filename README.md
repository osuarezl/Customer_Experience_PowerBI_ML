# Train Customer Experience - PowerBI dashboards for ML model training and predictions 

## __Technologies used__
- PowerBI
- Power Query
- DAX
- Python
- PyCaret

## __Description__
These dashboards are a practical example of how an ML solution can be deployed to solve a real-life business issue in PowerBi.

The MLModel dashboard outline:
- ETL logic in Power Query. 
- Python script to train several ML Models on the training data.
- Return the training results and creation of a Pickle file with the best model.
- Population of the dashboard with the training results.

The Predictor dashboard outline:
- ETL logic in Power Query. 
- Python script to retrieve ML model and make predictions on the data. 
- Population of the dashboard with the predicted outcomes and the status of the most relevant features (according to the model).

## __Business perspective__
The business wants to understand the satisfaction of their customer using their train lines.
A survey conducted is available and will be used to train an ML model to identify the features that drive the outcome of being satisfied or not. In addition, this ML model will be used to predict the “temperature” of the service experience by constantly feeding new data. 
Finally, using this information, decisions will be made to improve the service.

## __Notes__
-   An automatic ML process is followed for simplicity. 
-   Previous analysis and experimentation using Data Science and Machine Learning techniques are not shown.
-   The most important features were selected from several models in a previous exercise. But the same could have been achieved through a more complex Python script inside Power Query.
-   The training dashboard is also important to the business as a model with similar/enough performance to the top one could involve the use of fewer resources (complexity, cloud processing time, etc.). 

