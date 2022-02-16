## 起个名字：wrapper to the exchangerate.host API

This is a package to interface with the exchangerate.host API. The exchangerate.host is an API that can get the currency exchange rate and the history trend of the currency. 

For more information about the API, you can visit the website: https://exchangerate.host/#/

# Function

## currency_time_series

This function need the user input the start date, end date and the base currency and return dataframe of the currency exchange rate during the time period. 

    ```R
    currency_time_series("2020-01-01","2020-02-03","CAD")
    ```

## history_trend_plot

This function need the user input the start date, end date, base currency and the aim currency and return the plot of the currency exchange rate between the 2 currency during the time period.

    ```R
    history_trend_plot("2020-11-30","2021-01-03","CAD","USD")
    ```

