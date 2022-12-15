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
- site_id : Foreign key for the weather file (indicates a site location)
- building_id : Unique building ID
- primary_use : Indicator of the primary category of activities for the building based on EnergyStar property type definitions
- square_feet : Gross floor area of the building
- year_built : year_built
- floor_count : Number of floors of the building

2. Energy Consumption (about buildings enegy consumption from 01/01/2016 to 12/31/ 2017, it has 4 variables):
- building_id : Unique building ID
- meter : The meter (energy source) ID Code. Read as : 0: electricity, 1: chilledwate, 2: steam, 3: hotwater
- timestamp : When the measurement was taken (each hour)
- meter_reading: The target variable. Energy consumption in kWh (or equivalent). Not every building has all meter types

3. Weather (about the weather condition each hour per site from 01/01/2016 to 12/31/ 2017, it has 8 variables):
site_id : Foreign key for the Building file, 
air_temperature : Degrees Celsius, 
cloud_coverage : Portion of the sky covered in clouds, 
dew_temperature : Degrees Celsius, 
precip_depth_1_hr : Millimeters, 
sea_level_pressure : Millibar/hectopascals, 
wind_direction : Compass direction (0-360), 
wind_speed : Meters per second, 
timestamp : When the measurement was taken

IV. Deliverables

As part of this challenge, the client expects three deliverables from you:
The results obtained on the test data set submitted in csv format named name_of_your_group.csv with 4 columns in the following order: site_id, building_id, timestamp, meter_reading. The test data set will be provided 1 hours before the end of the Data Challenge.
A scientific procedure document presenting the proposed approach and the results obtained regarding the metric presented above.
A presentation of 7 min presenting your solution, its advantages, its feasibility to your client.
All deliverables must be sent by email to the following address mohamed.ihaddadene@capgemini.com, before 5pm on Thursday, October 27.

V. Challenge evaluation

Based on your deliverables, you are evaluated on 3 final criteria by a jury:
Model Performance: The solution delivers a satisfactory score for the metric used.
Innovation: Your ability to surprise the jury with the format and content of the "business" presentation and its application in a professional context (a clear and synthetic oral presentation, which creates the "Wow effect", is expected). In addition, the originality of the scientific procedure will be valued.
Scientific approach: Clarity, rigor, justification and relevance of your scientific approach, expressed on the scientific procedure document.

Please note:
We provide coaching sessions (30 minutes) with our experts to answer your questions. Feel free to reserve a time slot by providing the name of the team and the email address of a member of the group via the Doodle link.

The dataset test will be released at 4pm on Thursday, October 27.

VI. Benchmark

A first naive method to predict the energy consumption is to estimate it using the average of energy consumption on the training set, this will serve as a benchmark for the energy consumption predictions.
The proposed solution does not constitute a solution to be adopted to solve the challenge. It is presented to show you an example of a submission that meets the requirements.
