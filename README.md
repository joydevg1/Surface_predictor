# Surface_predictor

In the following code, a deep learning model has been created to predict the type of surface based on the input from different sensors over the period of time.

# About the Data
 
X_[train/test].csv - the input data, covering 10 sensor channels and 128 measurements per time series plus three ID columns:

-row_id: The ID for this row.

-series_id: ID number for the measurement series. Foreign key to y_train/sample_submission.

-measurement_number: Measurement number within the series.

y_train.csv - the surfaces for training set.

-series_id: ID number for the measurement series.

-group_id: ID number for all of the measurements taken in a recording session. Provided for the training set only, to enable more cross validation strategies.

-surface: the target for this competition

The final output of the following model is the surface type with respect to the series id.
