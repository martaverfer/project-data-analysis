# Socioeconomic and Environmental Data Analysis

## Project Overview

This project involves the analysis of various socioeconomic and environmental factors across differente countries.The goal is to explore and uncover meaningful insights regarding how factors like GDP, population density, health indicators, CO2 emissions, and more impact a country's development and overall well-being.

## Dataset

The dataset used in this project contains the following key features for each country:
- **Country**: Name of the country.
- **Density (P/Km²)**: Population density in persons per square kilometer.
- **Abbreviation**: Abbreviation or country code.
- **Agricultural Land (%)**: Percentage of land used for agricultural purposes.
- **Land Area (Km²)**: Total land area in square kilometers.
- **Armed Forces Size**: Size of the country's armed forces.
- **Birth Rate**: Number of births per 1,000 population per year.
- **Calling Code**: International calling code.
- **Capital/Major City**: Name of the capital or major city.
- **CO2 Emissions**: Total carbon dioxide emissions (in tons).
- **CPI (Consumer Price Index)**: A measure of inflation and purchasing power.
- **CPI Change (%)**: Percentage change in CPI compared to the previous year.
- **Currency Code**: The country’s currency code.
- **Fertility Rate**: Average number of children born to a woman during her lifetime.
- **Forested Area (%)**: Percentage of land covered by forests.
- **Gasoline Price**: Price of gasoline per liter in the country’s local currency.
- **GDP**: Gross Domestic Product.
- **Gross Primary Education Enrollment (%)**: Enrollment rate for primary education.
- **Gross Tertiary Education Enrollment (%**)**: Enrollment rate for tertiary education.
- **Infant Mortality**: Number of deaths per 1,000 live births before one year of age.
- **Largest City**: The largest city by population in the country.
- **Life Expectancy**: Average number of years a newborn is expected to live.
- **Maternal Mortality Ratio**: Number of maternal deaths per 100,000 live births.
- **Minimum Wage**: Minimum wage in local currency.
- **Official Language**: Official language(s) spoken in the country.
- **Out-of-Pocket Health Expenditure (%)**: Percentage of total health expenditure paid out-of-pocket by individuals.
- **Physicians per Thousand**: Number of physicians per 1,000 people.
- **Population**: Total population of the country.
- **Labor Force Participation (%)**: Percentage of the population that is part of the labor force.
- **Tax Revenue (% of GDP)**: Tax revenue as a percentage of GDP.
- **Total Tax Rate**: Overall tax burden as a percentage of commercial profits.
- **Unemployment Rate**: Percentage of the labor force that is unemployed.
- **Urban Population**: Percentage of the population living in urban areas.
- **Latitude**: Latitude coordinate of the country’s location.
- **Longitude**: Longitude coordinate of the country’s location.

## Objectives 

Multiple analyses will be performed, including:
- Correlation between CO2 Emissions and GDP to see if more industrialized countries emit more CO2.
- Compare CO2 Emissions with Population Density or Urban Population to understand how urbanization and density impact emissions.
- Examine Forested Area and GDP to assess if countries with more forested land are better off economically or have better environmental policies.

## Methodology

1. **Data Cleaning and Preprocessing:**
- Handle missing values, outliers, and data inconsistencies.
- Convert categorical variables into numerical format.
- Normalize or standarize numerical values where necessary to ensure compatibility for analysis and modeling.
2. **Exploratory Data Analysis (EDA):**
- Analyze summary statistics to identify patterns, trends, anomalies.
- Use various visualization techniques to better inderstand the distribution and relationships between the variables.
3. **Statistical Analysis:**
- Conduct correlation analysis to identify significant relationships between socioeconomic and environmental variables.
- Perform hypothesis testing where applicable to validate assumptions or draw conclusions.

## Installation

To run this project locally, follow these instructions:

1. **Clone this repository:**

```bash
git clone https://github.com/martaverfer/project-data-analysis.git \
cd python_scripts
```

2. **Virtual environment:**

Create the virtual environment: 
```bash
python3 -m venv venv
```

Activate the virtual environment:

- For Windows: 
```bash
venv\Scripts\activate
```

- For Linux/Mac: 
```bash
source venv/bin/activate
```

To switch back to normal terminal usage or activate another virtual environment to work with another project run:
```deactivate```

3. **Install dependencies:**

```bash
pip install --upgrade pip; \
pip install -r requirements.txt
```

4. **Open the Jupyter notebook to explore the analysis:**

```bash
cd python_scripts; \
main.ipynb
```

This script will execute the analysis steps and produce the results.

## Analysis and Results

- Economic Growth and Health: We found that GDP is strongly correlated with Life Expectancy, but the strength of the relationship varies by region.
- Education and Employment: Countries with higher Primary Education Enrollment have a higher Labor Force Participation, indicating a strong relationship between education and economic activity.
- Environmental Impact: There is a clear positive correlation between CO2 Emissions and GDP, with industrialized countries showing higher emissions per capita.

## Conclusion

This analysis provides valuable insights into how different socioeconomic, demographic, and environmental factors interact across countries. The findings can inform policymakers on the importance of balancing economic development with social and environmental sustainability.

## Additional content

- [Presentation](https://docs.google.com/presentation/d/1Dyra_VNvsXpuOuGQpgS10yfB4yp7ZI9L1NXkTc_QoeE/edit?usp=sharing)


