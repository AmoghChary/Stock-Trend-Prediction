STOCK TREND PREDICTION 

DESCRIPTION:
The app is built using Python and Streamlit, leveraging libraries such as yfinance for data collection and pandas for data handling. The predictive model is an LSTM (Long Short-Term Memory) neural network trained using Keras, known for its capability to process time series data effectively. Users can visualize closing price trends over time, compare actual vs. predicted prices, and analyze stock performance with the help of moving averages. This tool aims to simplify stock analysis, providing real-time insights and aiding in better investment strategies.

FEATURES:
Predicts stock trends using LSTM.

Data visualization for stock trends.

Implementation:

1.Using Sckiit Learning( Machine Learning model)

2.Data Preprocessing using dataset

3.Visualization of Dataset

4.Feature Scaling

5.Preparing the Datasets for training

6.Reshaping the datasets

7.Model development

8.Implementation of sequential, dense, LSTM.

9.Preprocessing the Data

10.Predicting the Output

11.Result visualization

### Installation Guide

Follow these steps to set up and run the stock trend prediction web app:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/username/stock-trend-prediction-app.git
   cd stock-trend-prediction-app
   ```

2. **Set Up a Virtual Environment** (Recommended):
   ```bash
   python -m venv venv
   source venv/bin/activate   # On Windows: venv\Scripts\activate
   ```

3. **Install Dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

4. **Download the Pre-trained Model**:
   Ensure that `keras_model.h5` is placed in the project directory.

5. **Run the Application**:
   ```bash
   streamlit run app.py
   ```

6. **Access the App**:
   Open your web browser and navigate to:
   ```
   http://localhost:8501
   ```

### Requirements
- Python 3.x
- Streamlit
- Keras
- TensorFlow
- Pandas
- NumPy
- Matplotlib
- yfinance

### Troubleshooting
- Ensure that all dependencies are installed correctly.
- For issues related to virtual environments, verify that the correct environment is activated.
- If encountering errors with `yfinance`, ensure you have an active internet connection.

This guide will help you set up and launch the app seamlessly.

