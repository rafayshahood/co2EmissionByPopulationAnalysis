# CO2 Emission Analysis by Population

## Project Overview
This project aims to analyze CO2 emissions influenced by population growth over the years. Utilizing datasets from *Our World in Data*, we explore the relationship between population sizes and CO2 emissions across different countries and periods. Our analysis covers data preprocessing, exploratory data analysis (EDA), data visualization, and predictive modeling using linear regression.

## Dataset
The primary dataset includes several attributes, but our focus is on six key features:
- `country`: The name of the country.
- `year`: The year of the record.
- `population`: The population of the country.
- `co2`: CO2 emissions measured in million tonnes.
- `co2_growth_prct`: The percentage growth of CO2 emissions.
- `temperature_change_from_co2`: Temperature change attributed to CO2 impact.

Source: Hannah Ritchie, Max Roser, Edouard Mathieu, Bobbie Macdonald, Pablo Rosado (2020) - "CO₂ and Greenhouse Gas Emissions". Our World in Data. [Online Resource](https://ourworldindata.org/co2-and-greenhouse-gas-emissions)

## Installation
To run this analysis, ensure you have Jupyter Notebook installed with the following Python libraries:
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

You can install the required packages using pip:
```bash
pip install notebook pandas numpy matplotlib seaborn scikit-learn
