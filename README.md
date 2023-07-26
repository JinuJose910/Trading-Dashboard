# Interactive Candlestick Chart Dashboard with Python

## Overview

This interactive dashboard project allows users to visualize historical stock prices using Python. 
The dashboard leverages the power of the Plotly library to create interactive candlestick charts, displaying open, high, low, and closing prices for any given stock symbol.
It fetches historical stock data from the Alpha Vantage API using Python's requests library.

## Features

- Interactive Candlestick Charts: Users can enter the stock symbol they want to visualize, and the dashboard will fetch and display the candlestick chart right in the browser.

- Historical Stock Data: The dashboard fetches historical stock data from the Alpha Vantage API, providing insights into stock trends and patterns.

- User-Friendly Interface: Simple and intuitive interface, making it easy for traders, investors, or anyone curious about stock data to use the dashboard effectively.

## Usage

1. Clone the repository to your local machine:

```bash
git clone https://github.com/your_username/candlestick-chart-dashboard.git
cd candlestick-chart-dashboard
```

2. Install the required dependencies:

```bash
pip install -r requirements.txt
```

3. Replace 'YOUR_API_KEY' in the code:

You will need to replace `'YOUR_API_KEY'` in the Python code with your actual Alpha Vantage API key. Don't have an API key? Get one for free from [Alpha Vantage](https://www.alphavantage.co/).

4. Run the application:

```bash
python app.py
```

5. Access the dashboard:

Open your web browser and go to `http://localhost:7860/` to access the dashboard. Enter the stock symbol you want to visualize, and the candlestick chart will be displayed.


## Technologies Used

- Python
- Plotly
- Requests
- Gradio (for deployment)

## Contributions

Contributions are welcome! If you find any issues or want to enhance the dashboard, feel free to open a pull request.
