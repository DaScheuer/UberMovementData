# UberMovementDataDownloadBot

This project aims to automate the download of daily travel time datasets from the Uber Movement website for my bachelor's thesis.

Uber Movement data is monochronic, meaning that if you choose to download travel times from January 2020 to March 2020, you won't get travel times fore each day in that date range. Rather, you'd get a csv file with one single value for the average travel times for the three months.

The "Uber Dataset Download Bot", in addition to the "Dataset Cleaner and Merger" builds time series data out of monochronic data, for any city available in the website.
