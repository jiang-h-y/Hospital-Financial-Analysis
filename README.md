# Hospital Financial Analysis

The sudden closures of hospitals due to financial stress devastates local communities, as patients must overcome barriers to accessing healthcare. This became an issue in the Boston area after the closures of Carney Hospital and Nashoba Valley Medical Center. 

This project aims to identify at-risk hospitals by applying K-means clustering to reported financial data.

## Dataset
The dataset includes hospital facilities from Massachusetts, California, and Washington.

https://www.chiamass.gov/hospital-and-hospital-system-quarterly-and-annual-financial-data/

https://www.google.com/url?q=https://catalog.data.gov/dataset/hospital-annual-financial-data-selected-data-pivot-tables-92074&sa=D&source=docs&ust=1747680158829105&usg=AOvVaw1RAThWqzdTC6EKMzFG5Mwt

https://data.wa.gov/dataset/HOFIDAR-Yearly-Balance-Sheet-and-Income-Statement/g3t6-ugwe/about_data


## Financial Ratios
These ratios were used to evaluate the financial health of the hospitals:
* Current Ratio (liquidity)
* Net Profit Margin (profitability)
* Debt Service Coverage Ratio (solvency)

## Cluster Interpretation
Hospitals were assigned to the following financial health categories:
* Healthy
* Some Long-Term Risk
* High Short-Term Risk
* Extremely High Risk

## Test Cases
Carney Hospital → Extremely High Risk

Nashoba Valley Medical Center → High Short-Term Risk
