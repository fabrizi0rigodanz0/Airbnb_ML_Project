# Airbnb Price Prediction Model

## Project Overview
This project aims to develop a machine learning model capable of predicting Airbnb listing prices in New York City based on a variety of listing features. Our goal is to enable hosts to set competitive and fair prices for their properties by providing accurate price predictions.

## Dataset Description
The dataset is a curated sample focusing on Airbnb listings in New York City. It encompasses a wide range of information, including host details, property characteristics, location data, and reviews. The dataset used in this project is taken from Kaggle:

[Airbnb Open Data on Kaggle](https://www.kaggle.com/datasets/arianazmoudeh/airbnbopendata/data)

### Features
- **ID**: Unique identifier for each listing
- **NAME**: Name of the listing
- **Host Details**: Including `host id`, `host name`, and `host_identity_verified` (whether the host is verified)
- **Location**: Including `neighbourhood`, `neighbourhood group`, `lat` (latitude), `long` (longitude), `country`, and `country code`
- **Booking Details**: Such as `instant_bookable` (whether the listing can be booked instantly) and `cancellation_policy`
- **Property Details**: Including `room type`, `Construction year`
- **Pricing Information**: Including `price` per night and `service fee`
- **Booking Conditions**: Such as `minimum nights` required for a booking
- **Reviews**: Including `number of reviews`, `last review` date, `reviews per month`, and `review rate number`
- **Listing Availability**: Including `calculated host listings count` (number of listings from the host) and `availability 365` (number of days available for booking in a year)
- **Additional Information**: `house_rules` and `license`

### Target Variable
- **Price**: The price per night of the Airbnb listing, which we aim to predict using the features mentioned above.

## Objectives
1. Conduct an Exploratory Data Analysis (EDA) to uncover insights and trends within the Airbnb listings in New York City.
2. Clean and preprocess the dataset, preparing it for the modeling phase.
3. Develop and train a machine learning model to predict the nightly price of Airbnb listings.
4. Evaluate the model's performance using appropriate metrics and identify key features that influence listing prices.

## Methodology
- **Data Cleaning**: Addressing missing values, standardizing column names, and converting appropriate data types.
- **Feature Engineering**: Developing new features potentially significant for price prediction.
- **Model Selection**: Experimenting with various regression models to find the most accurate predictor of price.
- **Evaluation**: Using evaluation metrics such as RMSE and R-squared to gauge model performance.

## Results
(Here, you will provide a summary of the model performance, including any interesting findings and insights derived from your project.)

## Getting Started
These instructions will guide you on how to get the project up and running on your local machine for development and testing purposes.

### Prerequisites
- Python 3.8 or higher
- Jupyter Notebook
- Libraries: pandas, numpy, scikit-learn, matplotlib, seaborn

### Installation
Clone the GitHub repository to your local machine:
- git clone https://github.com/fabrizi0rigodanz0/airbnb_ML_project.git

Install the required Python packages:
- pip install -r requirements.txt

### Running the Project
Open the project directory and launch Jupyter Notebook to explore the dataset and models.


## Authors
- Fabrizio Rigodanzo - [fabrizi0rigodanz0](https://github.com/fabrizi0rigodanz0)

## License
This project is licensed under the MIT License - see the [LICENSE.md](LICENSE) file for details.
