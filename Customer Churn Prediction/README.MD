# Churn Prediction and Analysis

## Overview
This project focuses on predicting customer churn using historical data and visualizing key insights through Power BI. The objective is to identify patterns and factors that lead to customer churn, enabling the business to implement strategies for customer retention.

## Table of Contents
- [Project Structure](#project-structure)
- [Data](#data)
- [Analysis](#analysis)
- [Visualizations](#visualizations)
- [Results](#results)
- [Tools Used](#tools-used)
- [How to Use](#how-to-use)
- [Contributing](#contributing)
- [License](#license)

## Project Structure
- **Data**: Contains the datasets used for analysis.
- **Scripts**: Python scripts (if applicable) for data preprocessing, feature engineering, and model building.
- **Visualizations**: Power BI file (`Churn Prediction.pbix`) that includes all dashboards and reports.
- **Documentation**: This README file and any other project-related documentation.

## Data
The dataset includes customer information such as:
- Geographic location (France, Germany, Spain)
- Credit score
- Gender
- Number of products owned
- Balance and estimated salary
- Activity status (IsActiveMember)
- Churn status (Exited)

## Analysis
The analysis involved several key steps:
1. **Data Cleaning and Preparation**: Ensured data quality by handling missing values, duplicates, and inconsistencies.
2. **Exploratory Data Analysis (EDA)**: Visualized the distribution of key variables and identified trends related to customer churn.
3. **Modeling**: Built machine learning models (if applicable) to predict churn based on historical data.
4. **Reporting**: Created an interactive Power BI dashboard to present the findings and support decision-making.

## Visualizations
Key insights are presented in the Power BI dashboard:
- **Churn Rate**: 28.34% of customers have exited, while 71.66% remain active.
- **Geographical Distribution**: France has the highest number of customers and contributes the most to the total balance.
- **Gender Analysis**: Males are more likely to remain active members, although credit card ownership is nearly equal between genders.
- **Financial Overview**: The total balance across customers is approximately 76.48 billion, with an estimated salary sum of 1 billion.

## Results
The analysis revealed critical factors contributing to customer churn, such as geographic location, product ownership, and gender. These insights can guide targeted strategies to improve customer retention.

## Tools Used
- **Power BI**: For data visualization and dashboard creation.
- **Python**: (if applicable) For data preprocessing, feature engineering, and modeling.
- **SQL/MySQL**: (if applicable) For data extraction and management.

## How to Use
1. Clone this repository.
2. Open the `Churn Prediction.pbix` file in Power BI to explore the dashboard.
3. (If applicable) Run the Python scripts to preprocess data and build predictive models.

## Contributing
Contributions are welcome! Please feel free to submit a pull request or open an issue for discussion.

## License
This project is licensed under the MIT License.

