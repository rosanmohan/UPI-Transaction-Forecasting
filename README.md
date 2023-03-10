
# UPI Transaction Forecasting Project

The UPI Transaction Forecasting project aims to predict the future patterns and trends in UPI transactions using historical transaction data and machine learning / deep learning techniques. The project will involve collecting, cleaning, analyzing, and transforming the data into a suitable format for machine learning. The selected machine learning model will then be trained on the data and used to make predictions about future UPI transactions. The results of this project will provide valuable insights into the future of UPI usage in India, which can be used by businesses, financial institutions, and government agencies to improve their services and offerings.


<img width="552" alt="image" src="https://user-images.githubusercontent.com/93364800/218988061-48ce267d-8d74-42d3-bfe0-bad467c74331.png">

## Prerequisites
Before you get started, you will need to have the following installed:

    Python 3
    NumPy
    Pandas
    Matplotlib
    Scikit-learn
    Pmdarima
    Darts
    Prophet


## Installing

To install the required packages, run the following command:

    pip install numpy pandas matplotlib scikit-learn pmdarima darts

## Data Collection

The first step is to collect historical UPI transaction data from reliable sources. The data should include information such as the date of the transaction and the transaction amount in crores. In this data we found the all India transactions through UPI in a Perticular date.


## Data Cleaning

The next step is to clean and preprocess the data to remove any missing or inconsistent values and ensure that it is ready for analysis. But in this case the data is quite simple, we don't have any missing or some other values to analyse. We have one date column and one values column.
## Data Analysis

The third step is to analyze the data to understand the patterns and trends in UPI transactions. This will involve exploring the data, creating visualizations, and performing statistical tests to identify any correlations or relationships in the data.

<img width="604" alt="image" src="https://user-images.githubusercontent.com/93364800/218988912-48628f25-214b-471a-885b-1de9ea13ba95.png">

## Modeling

The next step is to select an appropriate machine learning model to use for forecasting. This will involve considering the type of data, the forecasting horizon, and the accuracy required. Here we have tried multiple models to check which model is performing good. we have considered MAPE (mean absolute percentage error) as our error matix. 
    
Then we train the selected machine learning model on the historical UPI transaction data. This will involve selecting the appropriate parameters and hyperparameters and evaluating the model's performance.

After that finally to evaluate the performance of the trained model on a test dataset and compare its performance to other models. The model will be evaluated based on metrics MAPE as mentioned above and for by visualizing the values.

## Contributing

If you would like to contribute to this project, please follow these guidelines:

    Fork the repository.
    Create a branch with a descriptive name.
    Make your changes.
    Submit a pull request.
## Contact

If you have any questions or suggestions, please feel free to reach out to us at rosanmohans@gmail.com.
