![image](https://github.com/JITESHMD/SecondHanded-Mobile-GBR_MODEL/assets/121152161/228fa108-e2f4-40b3-828f-1619717a096b)# SecondHanded-Mobile-GBR_MODEL

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


<img alt="image" width="400" src="https://www.kaggleusercontent.com/kf/116957315/eyJhbGciOiJkaXIiLCJlbmMiOiJBMTI4Q0JDLUhTMjU2In0..WK2f_OxgNCljUZHyKoJl4Q.TOG0mJhMQYMT18m_6GJ4y2p4-PrXsltz8yKRHNGBRVbIFFDo6vq9O0KVTErKBe0AdTnvP7LeWpod6i3j_v5_-yLLUvGnodT2nEI3MNC434N_-bVlOa02_vUlqBnJVbAADLcm2zuPBfBL45Y5-oEZHtPmmDcDVrZ0sOc7TfGi3o6kAoefZSX65c4pM8PdzUaKtv8SojHbJ1PSgJF3EKn7_Dyi707Slfce5-toIdVVx4P1eE4UvaGScpwZcbrOh9MBTAy8NttXqoc0lrRZY9su20jt-0ooz8I3ZNmw-RqlZWmqIVBocZTte6nXkQLKvsuR4e1Hzd6x1Bs9aoFlTAM0P8MNbUfy7FFgVz7EtzxM8nNKyLoKvR3a21LDNnCIgXnQlb6CwnuRVueU3x8sOuvCOTGPG8DmSjczU4ro8FAvQKXIjcfb3vRWwgbHLRQIACcTtEHGe8OidNpdSbTvQxUuzhDnC3NkMfdRN9IkrVEQzIGckhe2Pz9DH0Y-0pxTasxvKD6Tdqg6QXEo7rhQk-4-lHEnKBcrAk9Z5wkAtqe9vHV2QUqn-7UxMLAhCHiv4jk_Tatoml_dWYZTrvDYr1cReY-i2_S2PxBIDqxetSH-k2kBONvzDHxITjEvaFo-h4vj_0sn-gY2ikVOI0-EQRZxcg.kQhq_tndwocelMYXZsRofA/__results___files/__results___24_1.png" >
