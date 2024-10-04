The dataset used in this predictive maintenance project contains several attributes, which are described below. The data represents machine parameters collected over time, and it is used to predict anomalies that might indicate equipment failure.

time: Timestamp representing when the data point was recorded. It was used to extract additional temporal features like hour, day, and month to enhance model performance. This feature was dropped after feature engineering.

y: The target variable indicating whether an anomaly was detected (binary).

0: No anomaly detected (normal operation).

1: An anomaly detected (potential failure).

x1, x2, ..., x60: These are sensor readings or operational parameters collected from the machine. They represent various attributes of machine behavior, such as temperature, pressure, vibration, and other metrics that can indicate machine health. The actual meaning of each attribute depends on the specific type of equipment being monitored.

hour: Extracted from the 'time' column, this feature represents the hour of the day when the data point was recorded.

day: Extracted from the 'time' column, this feature represents the day of the month when the data point was recorded.

month: Extracted from the 'time' column, this feature represents the month when the data point was recorded.

Additional Notes

The dataset contains about 18,000 rows of data collected over several days.

The features are used to predict machine anomalies, aiming to carry out maintenance before a machine breakdown occurs.

The dataset was cleaned and preprocessed by handling missing values, detecting outliers using Isolation Forest, and standardizing numerical features.

The SMOTE technique was used to handle the imbalance in the target variable, as anomalies are rare compared to normal operations.
