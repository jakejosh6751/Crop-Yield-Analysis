# Crop Yield Analysis

## Project Overview

## Key Objectives

## Key Insights & Recommendations
ANALYSIS:

1.	Year over year yield

2.	



## Techniques & Procedures

#### Data Cleaning and Transformation:

Renamed headers:

- Null column header (index) to Farm ID
- Area to Region
- Item to Crop Type
- hg/ha_yield to Yield (ton per hectare) and using the Transform > Standard > Divide to convert hg (hectogram) to ton by dividing by 10,000. [1 ton = 10,000 ha]
- average_rain_fall_mm_per_year to Average Rainfall (mm per year)
- pesticides_tonnes to Pesticide (ton)
- avg_temp to Average Temperature



Renamed Values (in the Crop Type column) using Transform > Replace Values;
- Plantains and others to Plantain & Others
- Potatoes to Potato
- Rice, paddy to Rice Paddy
- Soybeans to Soybean
- Sweet Potatoes to Sweet Potato
- Yams to Yam



#### Data Modeling:

#### Calculated Columns:

#### Key Measures:

#### Data Exploration and Visualization:

