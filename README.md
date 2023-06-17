# Supercharge Locations Dataset

This repository contains a dataset of supercharge locations. It includes information about various locations where supercharging stations are available. The dataset is in CSV format and can be found in the `data` directory.

## Dataset Information

The dataset provides the following information for each supercharge location:

- `LocationID`: A unique identifier for each location.
- `Latitude`: The latitude coordinate of the location.
- `Longitude`: The longitude coordinate of the location.
- `Address`: The address of the location.
- `City`: The city where the location is situated.
- `State`: The state where the location is situated.
- `Country`: The country where the location is situated.
- `PostalCode`: The postal code of the location.
- `SuperchargeLevel`: The level of supercharging available at the location.
- `Availability`: The availability status of the supercharge station.
- `Notes`: Additional notes or comments about the location.

## Data Analysis

In this repository, you will also find a Jupyter Notebook (`data_analysis.ipynb`) that demonstrates how to perform data analysis on the supercharge locations dataset using the Python library Pandas. The notebook showcases two methods for handling missing values in the dataset: `fillna` and `mapping`.

### Fillna Method

The `fillna` method is a convenient way to replace missing values with a specified value or using different strategies, such as forward fill or backward fill. In the notebook, we use the `fillna` method to replace missing values in specific columns with appropriate values based on the context.

### Mapping Method

The `mapping` method allows us to replace specific values in a column with desired values. In the notebook, we demonstrate how to use the `mapping` method to replace certain missing values in the dataset with more meaningful representations.

## Getting Started

To get started with this dataset and the data analysis notebook, follow these steps:

1. Clone this repository:

```shell
git clone https://github.com/Ahmad1993Aj/Supercharge_Stations_EDA.git
