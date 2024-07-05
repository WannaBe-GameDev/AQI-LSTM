# AQI Prediction Using LSTM Networks

This project involves designing and developing advanced Air Quality Index (AQI) prediction models using Long Short-Term Memory (LSTM) networks. The primary motivation was to compare the effectiveness of Stacked LSTM and Bidirectional LSTM networks for time series forecasting.

## Project Steps

### Data Preprocessing
- Imported and cleaned a comprehensive dataset from the Time Series Air Quality Data of India (2010-2023).
- Focused on feature reduction and merging similar features to enhance data quality.

### Feature Engineering
- Handled missing values, removed outliers, and resampled the data to ensure consistency and accuracy.

### Model Development
- **Stacked LSTM Model:** Developed and trained a Stacked LSTM model with three layers, optimizing its performance for AQI prediction.
- **Bidirectional LSTM Model:** Created a Bidirectional LSTM model to leverage the benefits of processing input sequences in both forward and backward directions for improved accuracy.

### Evaluation
- Evaluated both models using metrics such as Root Mean Squared Error (RMSE) and Mean Absolute Percentage Error (MAPE) to assess their prediction accuracy.
- Visualized the results by comparing actual vs. predicted PM2.5 levels, demonstrating the comparative effectiveness of both models.
- Results showed that, despite the higher accuracy of Bidirectional LSTM, Stacked LSTM was more efficient.

## Conclusion
This project demonstrates expertise in data preprocessing, feature engineering, and advanced deep learning techniques to solve real-world environmental challenges. The comparison highlights the trade-offs between model accuracy and efficiency, providing valuable insights for future AQI prediction efforts.
