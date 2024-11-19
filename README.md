# Market Size Analysis of Electric Vehicles

Market Size Analysis is the process of estimating the potential sales for a product or service within a particular market segment. In the context of electric vehicles (EVs), it involves assessing the total volume of EV registrations to understand the growth of the market, forecast future trends, and help stakeholders make informed decisions regarding production, infrastructure development, and policy-making.

The provided dataset contains the following columns, each representing different aspects of the electric vehicle (EV) population in the United States:
VIN (1-10): Partial Vehicle Identification Number.
County: The county in which the vehicle is registered.
City: The city in which the vehicle is registered.
State: The state in which the vehicle is registered. It appears that this dataset may be focused on Washington (WA) state.
Postal Code: The postal code where the vehicle is registered.
Model Year: The year of the vehicle model.
Make: The manufacturer of the vehicle.
Model: The model of the vehicle.
Electric Vehicle Type: The type of electric vehicle, e.g., Battery Electric Vehicle (BEV).
Clean Alternative Fuel Vehicle (CAFV) Eligibility: Eligibility status for clean alternative fuel vehicle programs.
Electric Range: The maximum range of the vehicle on a single charge (in miles).
Base MSRP: The Manufacturer’s Suggested Retail Price.
Legislative District: The legislative district where the vehicle is registered.
DOL Vehicle ID: Department of Licensing Vehicle Identification.
Vehicle Location: Geographic coordinates of the vehicle location.
Electric Utility: The electric utility service provider for the vehicle’s location.
2020 Census Tract: The census tract for the vehicle’s location.

**Objective:**

The primary objective of this analysis is to leverage historical EV registration data to understand the current market penetration of EVs, predict future market growth, and identify key trends and factors driving market expansion. The specific goals include:

Assess the historical growth trend of EV registrations.

Forecast future EV registrations based on historical trends.

Analyze the distribution of EV registrations across different models, makes, and geographical regions.

Estimate the market size and growth potential of the EV market for upcoming years.

**Data Cleaning:**

1. Convert date columns into datetime format.

2. Find the missing values in Numeric columns and Categorical columns.

3. Replace missing values in Numeric columns with their respective mean or median.

4. Replace missing values in Categorical columns with their respective mode.

**Data Visualization:**

1. Analysed the historical growth of EV's using Line plot.

2. Forecast the EV registrations for next 5 years using Line plot and Linear Regression Algorithm.

3. Distributionn of vehicle making using Histogram.

4. Analyze the distribution of EV registrations across different geographical regions using Maps.

**Conclusion:**

Market Size Analysis of EVs provides a comprehensive overview of the electric vehicle market.

Strong historical growth is observed in EV registrations, especially in recent years.

Tesla leads the market in terms of make and model popularity.

Urban regions dominate EV registrations, indicating better infrastructure and policy support in these areas.

Electric range analysis shows a diverse range of vehicle capabilities across models.

The forecast predicts continued expansion of the EV market in the coming years.

