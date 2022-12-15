# Energy-Consumption-of-buildings-Data-Challenge-
Energy Consumption of buildings Data Challenge - Capgemini x MINES de Paris

#### I. Challenge Background

Recent geopolitical events have made it necessary for us to reassess our energy consumption habits. This has led to a greater focus on reducing our use of gas and electricity in order to reduce our dependence on certain foreign sources of energy. In order to achieve this goal, many people have begun to explore alternative sources of energy, such as solar and wind power, as well as more efficient ways of using traditional sources of energy. Additionally, there has been an increased emphasis on conservation and energy-saving measures, such as using energy-efficient appliances and implementing strategies to reduce energy waste. This is a key point if we hope to meet the objectives of the 2015 Paris Conference on Global Warming (COP21) to limit global warming between 1.5°C and 2°C.

According to a 2021 study, buildings alone account for 44% of the energy consumed in France, ahead of the transport sector (31.3%). It is therefore crucial to understand which levers can be used to reduce the consumption of buildings and renovate them efficiently.

#### II. Challenge goals

We’ll develop accurate predictions of metered building energy usage in the following areas: chilled water, electric, natural gas, hot water, and steam meters. The data comes from over 1,000 buildings over a three-year timeframe.

With better estimates of these energy-saving investments, large scale investors and financial institutions will be more inclined to invest in this area to enable progress in building efficiencies.

#### III. Data Description

To carry out the task we will have at our disposal 3 sets of data providing various information:
1.  Building (about building meta-data, it has 6 variables):
- site_id, building_id, primary_use, square_feet, year_built, floor_count

2. Energy Consumption (about buildings enegy consumption from 01/01/2016 to 12/31/ 2017, it has 4 variables):
- building_id, meter, timestamp, meter_reading

3. Weather (about the weather condition each hour per site from 01/01/2016 to 12/31/ 2017, it has 8 variables): site_id, air_temperature, cloud_coverage, dew_temperature, precip_depth_1_hr, sea_level_pressure, wind_direction, wind_speed, timestamp,

#### IV. Deliverables

As part of this challenge, the client expects deliverables from us:
The results obtained on the test data set submitted in csv format named name_of_your_group.csv with 4 columns in the following order: site_id, building_id, timestamp, meter_reading. The test data set will be provided 1 hours before the end of the Data Challenge.
A presentation of 7 min presenting your solution, its advantages, its feasibility to our client, with the format and content of the "business" presentation and its application in a professional context.
