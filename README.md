# Electric Vehicle and Infrastructure Expansion in California

This project is the final project for the class of Urban Planning 229 Urban Data Science (UCLA, Spring '22) by Harrison Frahn and Ophelia Sin. 

-- Project Status: Ongoing. 

## Project Objective
The purpose of this project is to understand analyze EV sales trend and charger distribution within the State of California at the tract level. The ultimate goal is to provide insights for different levels of government as EV usage continues to expand within the state.
Through this project we are hoping to answer the following questions:
1. How are demographic characteristics relevant to EV presence? 
2. Is the number of EV chargers and hydrogen refueling facilities proportional to the number of EV in each zip code? Are there mismatches?
3. How can we use demographic characteristics to predict future EV sales (and need for future facility locations)?

### Methods Used
- Data Visualization
- Predictive Modeling
- Spatial Clustering

### Data Sources
- [Race, income, home ownership, housing types from U.S. Census Bureau American Community Survey 2020 5-Year Estimate](https://www.census.gov/programs-surveys/acs)
- [Electric Vehicle Sales by Zipcode from the California Energy Commission](https://www.energy.ca.gov/files/zev-and-infrastructure-stats-data)
- [Electric Vehicle Charging Station Locations from the U.S. Department of Energy](https://afdc.energy.gov/fuels/electricity_locations.html#/find/nearest?fuel=ELEC)
- [CalEnviroScreen 4.0](https://oehha.ca.gov/calenviroscreen/report/calenviroscreen-40)
- [2019 Cartographic Boundary Shapefile, 2010 ZIP Code Tabulation Areas for United States, 1:500,000](https://catalog.data.gov/dataset/2019-cartographic-boundary-shapefile-2010-zip-code-tabulation-areas-for-united-states-1-500000)

## Policy Recommendations
- California should accelerate its plan to fund charging infrastructure through the state's Clean Transportation Plan (https://www.energy.ca.gov/programs-and-topics/programs/clean-transportation-program/clean-transportation-funding-areas-0); right now, the plan is focusing more on construction along "highways and major thoroughfares", but this analysis shows a severe lack of chargers within cities themselves as well. 

- The state's EV financing program seems to be working well; perhaps TOO well. Since it was implemented in 2010 (https://ww2.arb.ca.gov/news/california-electric-vehicle-rebate-demand-exceeds-clean-vehicle-rebate-project-funding), state EV purchases have steadily increased, but charging infrastructure has not been able to keep pace, with construction severely lacking in most years except 2020 and 2021. If the state doesn't increase the pace of charger construction, it risks incentivizing citizens to purchase more EV's than the charging network can handle. 

- Finally, the state must ensure that the chargers that are being built are equitably distrubuted among different demographics. For example, the charger density in East LA tends to be lower than the density it (wealthier) West LA, and the same is often true of the Bay Area. The state has started to address this by funding purchases of private, in-home chargers for low-income residents (https://www.nrdc.org/experts/miles-muller/california-approves-novel-low-income-ev-charger-program), but it's important to address the public charger imbalance as well as the private one.

### Python packages Used
- pandas, geopandas, sckit-learn, seaborn, jupyter notebook
