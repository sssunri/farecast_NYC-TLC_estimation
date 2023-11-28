# Farecast NYC-TLC Estimation

![sample](https://i.postimg.cc/qB59HHL3/pexels-photo-1521580.webp)

<!-- Photo by Rodolfo Clix from Pexels: https://www.pexels.com/photo/panning-photography-of-yellow-taxi-1521580/ -->

## Summary

The optimization of taxi service operations is crucial to meet the dynamic demands of bustling cities like New York. Addressing issues related to service efficiency, resource allocation, and customer satisfaction becomes imperative in navigating the inherent complexity of urban transportation systems, shaped by factors such as traffic patterns, temporal variations, and diverse customer preferences.

This project delves into the intricate patterns and trends within New York City taxi service data, unveiling valuable insights to optimize both operational efficiency and customer satisfaction. Through comprehensive exploratory data analysis, the project uncovers temporal patterns, peak hours, and other factors influencing taxi service demand. Leveraging this understanding, the objective is to enhance service operations and effectively meet customer needs. Additionally, the project extends to predictive modeling, implementing algorithms like multiple linear regression, random forest, and XGBoost to develop and evaluate models for accurate fare and tip estimations.

![models](https://i.postimg.cc/NjwmKLDv/trips-by-hourly-passengers.png)

## Project Structure

The repository is organized with the following structure:

- **`fare_estimation.ipynb`:**
  This Jupyter Notebook contains the script for exploratory data analysis, model training, and evaluation specifically focused on fare estimation. It provides insights into patterns and trends in the NYC taxi service data related to fare calculations.

- **`generous_customers.ipynb`:**
  In this notebook, additional machine learning models are implemented to predict customers who are likely to provide tips. The models aim to identify patterns in customer behavior that contribute to tipping, enhancing our understanding of customer preferences and potentially improving overall service satisfaction.

### Acknowledgments

This project is inspired by the [Google Advanced Data Analytics Professional Certificate](https://www.coursera.org/professional-certificates/google-advanced-data-analytics) program, specifically the end-of-course portfolio project titled Automatidata.

This project utilises a subset of the [2017 Yellow Taxi Trip Data](https://data.cityofnewyork.us/Transportation/2017-Yellow-Taxi-Trip-Data/biws-g3hs) obtained from the New York City Taxi & Limousine Commission, originally published as part of the NYC Open Data program. The dataset, containing 22,699 rows representing different trips and 18 columns, was provided by the Google Advanced Data Analytics Professional Certificate program for the purpose of the end-of-course portfolio project. Invaluable insights into the dataset's attributes and their meanings were derived from the detailed [Data Dictionary](https://data.cityofnewyork.us/api/views/biws-g3hs/files/eb3ccc47-317f-4b2a-8f49-5a684b0b1ecc?download=true&filename=data_dictionary_trip_records_yellow.pdf) provided by the New York City Taxi & Limousine Commission. We acknowledge the contribution of both the NYC TLC and the Google program to the dataset used in this analysis.
