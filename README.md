# Air Quality, Pollution and Respiratory Diseases

> This repository is under construction. It has the objective to put together interesting materials about AQI. The notebook is a quick example on how to retrieve AQI Singapore and to manipulate (just a bit) the JSON response.

## Health Impact

![Data Providers](https://raw.githubusercontent.com/antoinedme/aqi-data/master/presentation/Slide02.jpeg)

## How to find data?

Challenges faced by open data platforms:
- Make accurate and real-time transport data available to the public
- Make this data available in an easy-to-use format
- Create a sustainable and collaborative data environment that drives innovation

![Data Providers](https://raw.githubusercontent.com/antoinedme/aqi-data/master/presentation/Slide03.jpeg)

The World Air Quality Project: https://aqicn.org

In March 2020, real-time Air Quality information is available for than 12,000 stations in 1000 major cities from 100 countries, thanks to the huge effort from the world EPAs (Environmental Protection Agencies).

GET Method to retrieve JSON Data from the platform:
```
https://api.waqi.info/feed/YOUR_CITY/?token=TOKEN_KEY
```
You need to register in order to get a token: https://aqicn.org/data-platform/token/

There are currently more than 30,000 known air quality monitoring stations in the world, out of which more than 12,000 are published on the World Air Quality Index project. In order to keep a high level on consistency, only stations with particulate matter (PM2.5/PM10) readings are published. The AQI standard for every single published station is based on the US EPA Instant-Cast standard. 

![AQICN Platform](https://aqicn.org/images/sources/worldmap-2019.03-large.jpg)

```
https://api.data.gov.sg/v1/environment/psi/?date=2017-01-01
```

## How to use them?


![AQ Maps Data](https://raw.githubusercontent.com/antoinedme/aqi-data/master/presentation/Slide04.jpeg)

![Monitoring Stations](https://raw.githubusercontent.com/antoinedme/aqi-data/master/presentation/Slide05.jpeg)



## What insights?

![Innovation](https://raw.githubusercontent.com/antoinedme/aqi-data/master/presentation/Slide11.jpeg)


The following datasets have been provided as a starter kit to get started with the competition. Let’s understand them briefly:
1. Global Power Plant Database by World Resources Institute(WRI)

The Global Power plant database is a fully open-sourced(licensed under CC-BY 4.0.) and a comprehensive database that includes details of powerplants around the world. The database covers approximately 30,000 power plants from 164 countries and includes both thermal and renewable power plants.
2. Sentinel 5P OFFL NO2

Sentinel-5 Precursor (Sentinel-5P) is an Earth observation satellite developed by ESA as part of the Copernicus Programme. The Copernicus Programme is dedicated to monitoring air pollution and Sentinel 5P Precursor is its first mission. It consists of an instrument called Tropomi (TROPOspheric Monitoring Instrument) which is a spectrometer to monitor ozone, methane, formaldehyde, aerosol, carbon monoxide, NO2 and SO2 in the atmosphere.

The OFFL/NO2 is a dataset that provides offline high-resolution imagery of NO2 concentrations

3. Global Forecast System 384-Hour Predicted Atmosphere Data

Global Forecast System(GFS) is a model that forecasts weather.The GFS is a coupled model, composed of an atmosphere model, an ocean model, a land/soil model, and a sea ice model which work together to provide an accurate picture of weather conditions

![alt text](https://cdn-images-1.medium.com/max/800/1*10SiCHb5aTr5zeTrHLMbVA.gif)

An animated image of GFS simulated total atmospheric ozone concentration

4. GLDAS-2.1: Global Land Data Assimilation System

This dataset provided by NASA ingest satellite- and ground-based observational data products, using advanced land surface modeling and data assimilation techniques, in order to generate optimal fields of land surface states and fluxes (Rodell et al., 2004a)

Mobility

The CENSAM, from Singapore-MIT Alliance for Research and Technology, conducted several works on using portable sensors in Singapore. One main area of study was performed on the transport system and its concentrations of air pollution. Vehicular combustion is a major source of aerosol pollution in urban areas. Thus, short commuting trips may contribute disproportionately to daily aerosol exposure due to proximity to traffic. The study investigated the variability in aerosol exposure for typical journeys in the main commercial district of Singapore. Journeys were compared over three different transportation modes: bus, taxi and Mass Rapid Transit (Singapore’s subway system).


https://www.kaggle.com/mhajabri/air-pollution-101
https://www.kaggle.com/niyamatalmass/let-s-analyze-our-air-that-we-take
