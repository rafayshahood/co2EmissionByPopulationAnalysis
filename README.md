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
pip install notebook pandas numpy matplotlib seaborn scikit-learn

## Usage

To execute the analysis:
1. Clone the repository to your local machine.
2. Open the `Co2ByPopAnalysis.ipynb` notebook in Jupyter Notebook or JupyterLab.
3. Run each cell in the notebook to reproduce the analysis.

## Key Findings
- Certain countries have been the major contributors to CO2 emissions over the past 40 years.
- A direct relationship exists between population growth and CO2 emissions.
- CO2 emissions have a significant impact on global temperatures, highlighting the environmental harm caused by increased emissions.
- The analysis also demonstrates the effectiveness of linear regression models in predicting CO2 emissions based on population data.

## Contributing
Contributions to this project are welcome. Please fork the repository and submit a pull request with your suggested changes.

## License
This project is licensed under the MIT License - see the LICENSE file in the repository for details.

## Citation
Data used in this project requires citation. The dataset is courtesy of Hannah Ritchie, Max Roser, and Pablo Rosado from Our World in Data. Full citation details are available in the notebook.
