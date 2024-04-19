
# Demand Forecasting for Hotel Bookings

## Overview
This project uses machine learning to forecast demand for hotel bookings. The analysis is based on a dataset from a real hotel in Portugal, focusing on various factors like booking time, length of stay, and client demographics. The goal is to predict cancellation probabilities and optimize hotel booking strategies.

## Features
- **Exploratory Data Analysis (EDA):** Visual and statistical analysis to understand the data better.
- **Feature Engineering:** Transformation and creation of new features to improve model performance.
- **Predictive Modeling:** Implementation of machine learning models to predict booking cancellations.
- **Evaluation:** Assessment of model performance using accuracy metrics like precision, recall, and F1-score.

## Installation
To run this project, you need Python and several libraries installed. You can install all dependencies using the following command:

```bash
pip install -r requirements.txt
```

## Usage
To run the notebook, ensure you have Jupyter installed. Start the server with:

```bash
jupyter notebook
```

Navigate to the `Demand Forecasting-Hotel Bookings.ipynb` file in the browser and run the cells sequentially to reproduce the analysis.

## Data
The dataset includes booking information such as dates, number of people, parking spaces, and cancellation status. All personally identifying information has been removed.

## Contributing
Contributions to this project are welcome. Please fork the repository, make your changes, and submit a pull request.


## Acknowledgments
- Thanks to the team at Microsoft Research for creating the DoWhy library, which inspired some of the causal inference techniques used in this project.
- Acknowledgment to the data providers for making this research possible.
