# SecondHanded-Mobile-GBR_MODEL

SecondHanded-Mobile-GBR_MODEL
# Project Overview
This project is a predictive model for the normalized used price of mobile devices based on various features such as device brand, operating system, screen size, camera, memory, battery, and other characteristics. The model is built using Gradient Boosting Regression (GBR) algorithm.

# Data
The dataset used in this project is "used_device_data.csv" which contains information about used mobile devices. The dataset includes the following features:

device_brand: The brand of the mobile device.
os: The operating system of the mobile device.
screen_size: The screen size of the mobile device.
4g: Whether the mobile device supports 4G connectivity.
5g: Whether the mobile device supports 5G connectivity.
rear_camera_mp: The megapixels of the rear camera.
front_camera_mp: The megapixels of the front camera.
internal_memory: The internal memory of the mobile device.
ram: The RAM of the mobile device.
battery: The battery capacity of the mobile device.
weight: The weight of the mobile device.
release_year: The year the mobile device was released.
days_used: The number of days the mobile device has been used.
normalized_used_price: The normalized used price of the mobile device.
normalized_new_price: The normalized new price of the mobile device.

# Data Preprocessing
The data preprocessing steps include:

Handling missing values: The missing values in the dataset were filled using the mean of the respective columns.
Encoding categorical variables: The categorical variables (device_brand, os, 4g, 5g) were encoded using LabelEncoder.
Skewness reduction: The skewness of some columns was reduced by applying square root or logarithm transformations.

# Model Training
The Gradient Boosting Regression (GBR) algorithm was used to train the model. The following hyperparameters were used:

n_estimators: 3
max_depth: 3
learning_rate: 1
criterion: 'mse'
The model was trained on 80% of the data, and the remaining 20% was used for testing.

# Model Evaluation
The model's performance on the test set will be evaluated using appropriate metrics, such as Mean Squared Error (MSE) or R-squared.
