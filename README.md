# Global-CO2-emissions-dashboard
Power BI dashboard visualizing 250 years of global CO2 emissions

# Global CO2 Emissions Dashboard

This repository contains a Power BI dashboard that visualizes 250 years of global CO2 emissions data, offering insights into the world's top emitters and the correlation between population and CO2 emissions. The dashboard also emphasizes the impact of emissions on vulnerable countries, such as Pakistan, and highlights the urgency for global climate change policies.

## Tools & Technologies
- Power BI: For creating interactive dashboards.
- Power Query: For data extraction and cleaning.


## Data Source
The dataset used for this project is visualizing_global_co2_data.csv, which provides information about global CO2 emissions over the past 250 years.


1️⃣ Connected to the visualizing_global_co2_data.csv and familiarized myself with the dataset.

Analyzed which countries are the largest contributors to CO2 emissions.
2️⃣ Applied a data source filter to exclude NULL ISO Codes for accurate country-level analysis.

3️⃣ Converted all fields with "CO2" in their names to Number (Whole) data type and changed them to be continuous measures.

4️⃣ Created a new integer parameter "Top N" with a default value of 10 to dynamically filter the top CO2-emitting countries

## Key Features of the Dashboard:
1. Top N Emission Countries: Analysis of the top contributors to CO2 emissions across different time periods.
2. CO2 Per Capita (2021): Interactive map showcasing CO2 emissions per capita for each country.
3. Population vs. CO2 Emissions: Scatter plot comparing population and CO2 emissions, with bubbles sized by temperature change from CO2 in 2021.
4. Emerging Emission Players: Identifies new countries like Indonesia, Iran, Saudi Arabia, and South Korea that have emerged as significant emitters in recent years.

## Key Insights:
- The USA remains a leading emitter despite its relatively stagnant population.
- China's CO2 emissions are directly proportional to its large population.
- Emerging emitters such as Indonesia, Iran, Saudi Arabia, and South Korea are gaining prominence in CO2 emission.
- Pakistan, one of the least CO2-emitting countries, remains 5th most climate-affected countries.


