![image](https://github.com/TuncerCemUgurluer/NILM/assets/159438469/19c03300-3e46-428a-87e0-8928c45f3328)



# Project Description
This project focuses on Non-Intrusive Load Monitoring (NILM), which involves identifying and monitoring individual appliances' energy usage from aggregate power consumption data. The goal is to develop a system capable of accurately disaggregating energy usage data to identify various appliances in a household without the need for intrusive sensors on each appliance.

## Features
- **Data Collection**: The project collects energy consumption data from various households using non-intrusive methods such as smart meters or whole-house power monitors.
- **Data Preprocessing**: The collected data is preprocessed to remove noise, handle missing values, and prepare it for training machine learning models.
- **Model Training**: Machine learning models such as XGBoost and k-Nearest Neighbors (KNN) are trained on the preprocessed data to learn the patterns and characteristics of different appliances' energy usage.
- **Appliance Identification**: Trained models are used to predict the energy consumption patterns of individual appliances from aggregate power consumption data. This process helps in identifying and monitoring specific appliances in real-time without the need for additional sensors.

## Code Structure and Usage
The codebase consists of several components:

1. **Data Collection**: Energy consumption data is collected from households using non-intrusive monitoring devices and stored in CSV format.
2. **Data Preprocessing**: The collected data is loaded into Pandas DataFrames and preprocessed to handle missing values and remove unnecessary columns.
3. **Model Training**: Machine learning models, including XGBoost and KNN, are trained on the preprocessed data to learn the relationships between aggregate power consumption and individual appliances' energy usage.
4. **Appliance Identification**: Trained models are used to predict the energy consumption patterns of individual appliances from aggregate power consumption data. Visualization techniques are applied to interpret and analyze the model predictions.
