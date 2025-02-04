Stock analysis with TimeSeries model<br>
Workflow:<br>
1. Extract data using yfinance<br>
2. Clean the data<br>
3. Feature selection for the corresponding model<br>
4. For LSTM model, adjust the window_size and train test splitting<br>
5. Construct the model<br>
6. Train the model<br>
7. Test the model using the test data<br>
8. Adjust the hyperparameters
9. For Prophet model, directly fit the model to the prepared data for Prophet training
10. Test the model
