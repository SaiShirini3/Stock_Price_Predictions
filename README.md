# Stock Price Predictions with LSTM

## Project Overview
This repository hosts a Python project for predicting the next day's stock prices of the S&P 500 index using a Long Short-Term Memory (LSTM) network. The project utilizes PyTorch, a powerful library for building neural networks. The LSTM model featured in this project includes one hidden layer and is optimized using the Adam optimizer.

## Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [Model Architecture](#model-architecture)
- [Dataset](#dataset)
- [Model Training and Evaluation](#model-training-and-evaluation)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgments](#acknowledgments)

## Installation
To set up a local development environment, follow these steps:
1. Clone the repository:
git clone https://github.com/yourusername/Stock_Price_Predictions.git



## Usage
To run the stock price prediction model, navigate to the project directory and execute:
run Stock_Price_Prediction.ipynb

This will start the data preprocessing, model training, and evaluation sequence.

## Model Architecture
The LSTM model is designed with the following architecture:
- **Input Layer**: Accepts sequence data representing stock prices.
- **LSTM Layer**: Processes the input data with one hidden layer.
- **Output Layer**: Generates the prediction for the next day’s stock price.

## Dataset
The dataset consists of daily closing prices of the S&P 500 index and is loaded from a CSV file. Details on the data structure and preprocessing steps are as follows:
- **Data Loading**: Load data from `data/sp500.csv`.
- **Data Preprocessing**:
  - Scale data to a range between 0 and 1 to normalize.
  - Format data into sequences suitable for time-series prediction.

## Model Training and Evaluation
- **Training**: The model is trained using the Adam optimizer with a loss function suited for regression.
- **Evaluation**: Model performance is evaluated using Mean Squared Error (MSE) on a separated test set.


## License
This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.

## Acknowledgments
- The developers of PyTorch for providing an efficient and straightforward framework for deep learning applications.
- Contributors to the open-source community who maintain the tools and libraries used in this project.
