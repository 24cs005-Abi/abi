# Daily Climate Time Series Forecasting Using LSTM

## Project Overview
This project uses a Long Short-Term Memory (LSTM) neural network to predict daily mean temperature using historical weather data.

## Dataset
The project uses daily climate data with the following weather features:
- Mean temperature
- Humidity
- Wind speed
- Mean pressure

## Data Preprocessing
- Handled missing values.
- Removed duplicate dates.
- Used at least 1,000 consecutive daily records.
- Split the dataset chronologically into training, validation, and test sets.
- Fitted the scaler on training data only.

## Model
A sequential LSTM neural network was trained on historical weather sequences to forecast mean temperature.

## Evaluation Metrics
The model is evaluated on unseen test dates using:
- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)
- R² score

## Visualizations
- Actual versus predicted temperature graph
- Future temperature forecast graph

## Project Outputs
- Trained LSTM model
- Test predictions
- Evaluation metrics
- Future temperature forecasts

## Tools Used
- Python
- Google Colab
- TensorFlow/Keras
- Pandas and NumPy
- Matplotlib
- Scikit-learn

## How to Run
1. Open `download.ipynb` in Google Colab.
2. Upload the required climate dataset files.
3. Run the notebook cells in order.
4. Review the evaluation metrics, graphs, and forecasts.

## Limitations
Future forecasts depend on historical patterns and the model's assumptions. They should not be treated as official weather predictions.
