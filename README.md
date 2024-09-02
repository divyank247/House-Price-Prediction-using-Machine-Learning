# House Price Prediction Project

In this project, I utilized the California Housing dataset, which includes the following features:
- **Median Income (MedInc)**
- **House Age**
- **Average Rooms (AveRooms)**
- **Average Bedrooms (AveBedrms)**
- **Population**
- **Average Occupants (AveOccup)**
- **Latitude**
- **Longitude**

## Data Exploration and Visualization

I explored the dataset and created a heatmap using Matplotlib and Seaborn to visualize the correlations among different parameters. This analysis provided insights into the relationships between features and their potential impact on house prices.

## Model Training

The dataset was divided into training and testing sets. I employed the XGBRegressor algorithm to train the model, leveraging its effectiveness in regression tasks.

## Model Evaluation

To evaluate the performance of the model, I used R squared and Mean Absolute Error (MAE) metrics. The results indicate that the model performs exceptionally well, delivering accurate predictions for house prices.

