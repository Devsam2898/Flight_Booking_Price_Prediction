# Flight Booking Price Prediction

This repository contains code and resources for predicting flight booking prices using machine learning algorithms.

## Table of Contents

- [Overview](#overview)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Features](#features)
- [Models](#models)
- [Evaluation](#evaluation)
- [Contributing](#contributing)
- [License](#license)

## Overview

Flight booking price prediction is an essential task in the airline industry to help travelers plan their journeys and airlines optimize ticket pricing. This project aims to build a machine learning model to predict flight booking prices based on various features such as departure and arrival cities, travel dates, airline, and more.

## Dataset

The dataset used for this project is available in the `data` directory. It contains historical flight booking data with features like 'Departure City', 'Arrival City', 'Departure Date', 'Airline', 'Number of Stops', 'Duration', and 'Price' (target variable).

## Installation

To run the code and experiments, you will need Python 3.x and the following libraries:

```bash
pip install numpy pandas scikit-learn matplotlib seaborn
```

## Usage

1. Clone this repository to your local machine.
2. Navigate to the project directory.
3. Run the Jupyter notebook `Flight_Booking_Price_Prediction.ipynb` to train and evaluate the models.

## Features

The main features used for predicting flight booking prices are:

- Departure City
- Arrival City
- Departure Date
- Airline
- Number of Stops
- Duration

## Models

The project employs several regression models for price prediction, including:

- Linear Regression
- Decision Tree Regressor
- Random Forest Regression


## Evaluation

The models are evaluated using various metrics such as Mean Absolute Error (MAE), Mean Squared Error (MSE), Root Mean Squared Error (RMSE), and R-squared (R2) score.

## Contributing

Contributions to this project are welcome. If you find any issues or have suggestions for improvement, feel free to submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).
