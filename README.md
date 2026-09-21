# Stock Market Prediction App

This project predicts stock prices using a trained Keras model and displays the result in a Streamlit web app.

## Requirements

```bash
pip install -r requirements.txt
```

## Run

```bash
streamlit run app.py
```

## Project files

# 📈 Stock Market Predictor

An interactive **Streamlit** web application for stock price analysis and future price forecasting using a deep learning model.

---

## 📁 Project Structure

```text
├── app.py                                     # Streamlit web application interface
├── Stock Predictions Model.keras               # Pre-trained deep learning model
├── Stock_Market_Prediction_Model_Creation.ipynb # Jupyter Notebook for training & building the model
├── requirements.txt                           # Python dependencies
├── images/                                    # Screenshots for project documentation
└── README.md                                  # Project overview and instructions


## Notes

- Make sure your environment has internet access for Yahoo Finance data.
- The app downloads stock data using `yfinance`.
