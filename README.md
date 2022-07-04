# Internship for AI COVID Warrior Winners
Utilities and supplements for student winners of AI COVID Warrior Contest

## Task 1
### Objective
To analyze the intensity and efficacy of various SARS-Cov-2 variants through hospitalization and fatality numbers.

### Description
Since December 2020, several coronavirus variants have been identified and are under investigation. Each new variant raises questions: Are people more at risk for getting sick? How is this variant different from the previous one? Is this variant of concern?

Historic data can answer these questions through investigative analysis. There were multiple variants of concern - like beta, gamma, delta and omicron - each having their own active period which lasted from few weeks to few months. The task here is to analyze the number of hospitalizations and number of deaths that occurred in India during the active period of each variant. The severity of each variant should be ordered from high to low.

The participants are also encouraged to investigate the lesser known variants which did not become a variant of concern. Severities of these variants can also be included in the discussion.

### Data Sources
- [Active periods of variants](https://www.who.int/en/activities/tracking-SARS-CoV-2-variants/)
- [COVID-19 cases data](https://www.worldometers.info/coronavirus/country/india/)


## Task 2
### Objective
To predict Air Quality Parameters for a given place in India using time series modeling

### Description
The Air Quality Index is based on measurement of particulate matter (PM2.5 and PM10), Ozone (O3), Nitrogen Dioxide (NO2), Sulfur Dioxide (SO2) and Carbon Monoxide (CO) emissions. When AQI values are above 100, air quality is unhealthy: at first for certain sensitive groups of people, then for everyone as AQI values get higher.

Using time series modeling, we can predict the future AQI values based on the historic AQI data. Center for Pollution Control Board (CPCB) has been publishing AQI data for over 350 stations all over India on a 4-hourly basis. Building prediction models over that and inferring the future AQI values will provide us insights on how air quality will improve or worsen.

Participants are encouraged to use any established time series prediction model. The task will be to use 13 consecutive days of historic AQI data to predict AQI value for the 14th day.

### Data Sources
- [Raw CSV file](./airquality_data.csv)
- [National AQI Dashboard](https://app.cpcbccr.com/AQI_India/#)
