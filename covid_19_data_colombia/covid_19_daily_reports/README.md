# Daily reports (covid_19_daily_reports)

This folder contains daily case reports. Each file contains a table with the aggregation of each City or Municipality data. 
 
## File naming convention
MM-DD-YYYY.csv in UTC.
 
## Field description
**City/Municipality:** The name of the City or Municipality within Colombia. The Municipalities (municipios, in Spanish) are decentralized subdivisions of the Republic of Colombia. The Municipalities make up most of the departments of Colombia with 1,122 municipalities. 

**Department:** The name of the Department. Colombia is a unitary republic made up of thirty-two departments (departamentos, in Spanish) and a Capital District (BOGOTÁ D.C.). Departments are country subdivisions with a certain degree of autonomy. A grouping of municipalities forms departments.

**Latitude:** Is a geographic coordinate that specifies the north-south position of a point on the Earth's surface.

**Longitude:** Is a geographic coordinate that specifies the east-west position of a point on the Earth's surface.

**Active:** The number of aggregated confirmed cases that have not been resolved (Active = Confirmed - Recovered - Deaths).

**Confirmed:** The number of cases aggregated confirmed by the state. We report both clinically diagnosed and lab-confirmed cases. For more information, please refer to covid_19_situation_reports. 

**Deaths:** The number of aggregated confirmed deaths reported by the state.

**Recovered:** The Recovered case count reported by the state.

**House:** The number of patients treated in your house.

**Hospital:** The number of patients treated in the hospital.

**ICU:** The number of patients treated in an intensive care unit.

**People_Hospitalized:** Total number of people hospitalized (People Hospitalized = Hospital + ICU).

**Hospitalization_Rate:** Total number of People Hospitalized / Number of Confirmed Cases.

**Mortality_Rate:** Number of recorded Deaths / Number Confirmed Cases.

**Last Update:** The date of the official report. MM/DD/YYYY HH: mm (24-hour format, in UTC).
  
## Update frequency 
Once a day around 00:00 (UTC). 
  
## Data sources 
For more information, please refer to the [main page](https://github.com/CovidDataProject/DataCovid19Colombia).



---
[The COVID-19 Colombia Project](https://coviddataproject.com/)
