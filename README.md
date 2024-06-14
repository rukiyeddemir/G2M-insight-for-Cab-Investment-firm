# G2M Insight for Cab Investment Firm

XYZ is a private firm in the US. Due to the remarkable growth in the cab industry in recent years and multiple key players in the market, XYZ is planning to invest in the cab industry. As per their Go-to-Market (G2M) strategy, they want to understand the market before making a final decision. This project involves analyzing the provided datasets to generate actionable insights to help XYZ identify the right company to invest in.

## Table of Contents

- [Project Description](#project-description)
- [Datasets](#datasets)
- [Installation](#installation)
- [Analysis and Insights](#analysis-and-insights)
- [Visualization](#visualization)
- [Results](#results)
- [Recommendations](#recommendations)
- [Contributing](#contributing)
- [License](#license)

## Project Description

This project aims to analyze the performance of two cab companies based on various datasets provided. The goal is to deliver a comprehensive analysis and present actionable insights to XYZ's executive team to help them make an informed investment decision.

## Datasets

The following datasets were provided for the analysis:

1. **Cab_Data.csv** - Details of transactions for 2 cab companies
2. **Customer_ID.csv** - Mapping table containing unique identifiers linking customer demographic details
3. **Transaction_ID.csv** - Mapping table containing transaction-to-customer mapping and payment mode
4. **City.csv** - List of US cities, their population, and the number of cab users

## Installation

To run this project locally, follow these steps:

1. Clone the repository:
    ```sh
    git clone https://github.com/rukiyeddemir/G2M-insight-for-Cab-Investment-firm.git
    cd G2M-insight-for-Cab-Investment-firm
    ```

2. Install the required packages:
    ```sh
    pip install -r requirements.txt
    ```
## Analysis and Insights
The analysis includes the following steps:
Data Loading and Cleaning
Exploratory Data Analysis (EDA)
Customer Segmentation
Profitability Analysis
Churn Analysis
Customer Lifetime Value (CLV) Calculation

## Visualization
Several visualizations were created to aid in the analysis, including:
Histograms and Box Plots for key variables
Correlation Matrix
Time Series Plots for trends over time
Scatter Plots for customer segmentation
Bar Charts for payment mode distribution

## Results
Key insights derived from the analysis:
Yellow Cab has a larger market share and higher total revenue compared to Pink Cab.
The customer segments identified provide a clear picture of the demographics and travel behaviors.
Profitability varies significantly across different cities, with New York being the most profitable.

## Recommendations
Based on the analysis, the following recommendations were made:
Invest in Yellow Cab due to its larger market share and higher revenue potential.
Implement targeted marketing strategies to re-engage churned customers.
Develop loyalty programs to retain high-value customers, particularly in Cluster 2 (middle-income segment).

## Contributing
Contributions are welcome! Please open an issue or submit a pull request for any changes or improvements.

## License
This project is licensed under the MIT License. See the LICENSE file for details.
