# NYC Trip Duration Prediction

This project aims to predict the trip duration of taxi rides in New York City (NYC) by combining NYC weather data and trip data. The prediction model can be useful for estimating travel times and optimizing transportation services.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Data](#data)
- [Models](#models)
- [Evaluation](#evaluation)
- [Contributing](#contributing)
- [License](#license)

## Installation

To use this project, follow these steps:

1. Clone the repository:
git clone https://github.com/rashant/NYC-Trip-Duration-Prediction.git


2. Install the required dependencies. It is recommended to use a virtual environment:
cd NYC-Trip-Duration-Prediction
pip install -r requirements.txt

3. Obtain the necessary datasets:
- https://www.kaggle.com/c/nyc-taxi-trip-duration
- https://www.kaggle.com/datasets/cabaki/knycmetars2016

## Usage

1. Run the Jupyter notebook `data_collection_loading.ipynb`:

This notebook contains the code for reading the trip data and the weather data. Also the code further helps in combining both data which will be further used as the main dataset.

2. Run the Jupyter notebook `preprocessing_feature_engineering.ipynb`:

This notebook contains the code for data preprocessing, feature engineering and feature selection.

3. Run the Jupyter notebook `model_training.ipynb`:

This notebook contains the code for model training, predictions and evaluation.

## Data

The project utilizes two main datasets:

- **Trip Data**: This dataset contains information about taxi trips in NYC, including pickup and dropoff coordinates, pickup and dropoff timestamps, and trip duration.

- **Weather Data**: This dataset contains weather information for NYC, including temperature, precipitation, humidity, and wind speed. 

You can obtain the datasets from the following sources:

- [Trip Data](https://www.kaggle.com/c/nyc-taxi-trip-duration)

- [Weather Data]([https://openweathermap.org/](https://www.kaggle.com/datasets/cabaki/knycmetars2016))


## Models

The project utilizes various machine learning models for trip duration prediction. These models are implemented using the python libraries. The models used in this project include:

- Light GBM Regression
- XGBoost Regression


## Evaluation

To evaluate the performance of the prediction models, we use the mean aboslute error (MAE) as the evaluation metric. The lower the MAE, the better the model's performance. The evaluation results are discussed in detail in the `model_training.ipynb` notebook.
