# HouseRentAnalyzer

**HouseRentAnalyzer** is a project designed to collect, preprocess, build, deploy, and visualize data related to house rentals. 
## In this project

- **Data Collection**: 
  - Crawls rental data using Selenium from [batdongsan.com.vn](https://batdongsan.com.vn/).
  - Saves raw data in JSON format for further processing.

- **Data Processing**:
  - Identifies and fills missing values in the dataset.
  - Extracts district information from addresses.
  - Replaces IDs with meaningful terms for better interpretability.

- **Model Building**:
  - Constructs a model to predict rental prices, specifically targeting cases where `Price` is marked as `'Thỏa Thuận'`.

- **Model Deployment**:
  - Deploys the model to allow users to input rental information and receive predicted rental prices.


