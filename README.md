# Case_Study_-_III-Sensor
Case_Study_-_III Sensor_Acadgild

For this data analysis, you can download the necessary dataset from this link.
In the above link there are two datasets; building.csv contains the details of the top
20 buildings all over the world and HVAC.csv contains the target temperature and the
actual temperature along with the building Id.

HVAC (heating, ventilating/ventilation, and air conditioning) is the technology of
indoor and vehicular environmental comfort. Its goal is to provide thermal comfort and
acceptable indoor air quality. Through the HVAC sensors, we will get the temperature
of the buildings.

Here are the columns that are present in the datasets:
Building.csv – BuildingID, BuildingMgr, BuildingAge, HVACproduct,Country
HVAC.csv – Date, Time, TargetTemp, ActualTemp, System, SystemAge, BuildingID

Objective- 1
● Load HVAC.csv file into temporary table
● Add a new column, tempchange - set to 1, if there is a change of greater than +/-5 between actual
and target temperature

Objective- 2
Load building.csv file into temporary table

Objective - 3

Figure out the number of times, temperature has changed by 5 degrees
or more for each country:

○ Join both the tables.
○ Select tempchange and country column
○ Filter the rows where tempchange is 1 and count the number of
occurrence for each country
