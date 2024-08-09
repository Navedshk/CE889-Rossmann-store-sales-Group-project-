
## CE889 Rossmann Store Sales - Neural Network Project

This project focuses on predicting future store sales for Rossmann using Long Short-Term Memory (LSTM) networks. The core of the project is encapsulated in the Jupyter notebook `Neural_Networks_GroupAssignment_LSTM.ipynb`, which showcases the application of LSTM networks for time series forecasting with the Rossmann store sales dataset.

### Project Overview

The objective of this project is to leverage historical sales data from Rossmann stores to forecast future sales. This is achieved through the use of LSTM networks, which are well-suited for capturing complex temporal dependencies in time series data. The project involves several key steps, including data preprocessing, model development, training, and evaluation.

### Key Components

1. **Data Preprocessing**: 
   - **Data Cleaning**: The dataset is cleaned to handle missing values, outliers, and other inconsistencies.
   - **Feature Engineering**: Features are engineered to enhance the model's performance, including date-related features and store-specific attributes.
   - **Normalization**: Data is normalized to ensure that the model trains effectively and converges quickly.

2. **LSTM Model**:
   - **Model Architecture**: An LSTM network is designed to process sequential data, capturing long-term dependencies and trends.
   - **Training**: The model is trained using historical sales data, with techniques such as batch normalization and dropout employed to prevent overfitting.
   - **Hyperparameter Tuning**: Hyperparameters like learning rate, number of layers, and units per layer are tuned for optimal performance.

3. **Evaluation**:
   - **Performance Metrics**: The model's accuracy is assessed using metrics such as Mean Absolute Error (MAE) and Root Mean Squared Error (RMSE).
   - **Visualizations**: The notebook includes visualizations of training and validation loss, as well as forecasts compared to actual sales.

### Getting Started

1. **Install Dependencies**: Ensure you have the required Python libraries installed, including `numpy`, `pandas`, `matplotlib`, `tensorflow`, and `scikit-learn`.

2. **Run the Notebook**: Open `Neural_Networks_GroupAssignment_LSTM.ipynb` in a Jupyter environment, execute the cells sequentially, and observe
