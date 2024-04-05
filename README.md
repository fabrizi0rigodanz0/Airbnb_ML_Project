# Airbnb Price Prediction Model

## Introduction
Airbnb Pricing Inc. embarked on a mission to enhance pricing strategies for Airbnb hosts in New York City by leveraging advanced machine learning techniques. This project, stemming from a comprehensive study, offers precise, data-driven pricing recommendations to optimize Airbnb listing prices.

## Project Overview
Our aim is to empower Airbnb hosts to set competitive and equitable prices for their properties. Utilizing a dataset of over 100,000 unique Airbnb listings, we've developed a model that identifies key price influencers, enabling hosts to make informed pricing decisions based on a variety of listing features.

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
Our approach encompasses data preparation, exploratory analysis, and the application of linear and tree-based regression models, culminating in the selection of the Random Forest Regressor for its superior accuracy and generalizability.

## Results
Identification of critical price influencers and variations across neighborhoods.
The Random Forest Regressor emerged as the most effective model, balancing accuracy with computational efficiency.

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
Credit to the project team, highlighting contributions from Robert Helmut Münchau, Julia Antonioli, Kuba Bialczyk, and Nicolò Mazzoleni. Special thanks to Prof. Nuno André da Silva for guidance.

## License
This project is licensed under the MIT License - see the [LICENSE.md](LICENSE) file for details.
