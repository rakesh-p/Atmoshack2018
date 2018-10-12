# Atmoshack2018
Join EUMETSAT, ECMWF, FMI and University of Helsinki scientists for a weekend hackathon working with atmospheric data at the Finnish Meteorological Service in Helsinki on 16-18 November 2018. 

This Github repository contains the resources for Copernicus Hackathon 2018 in Helsinki. More info at https://ultrahack.org/atmoshack2018
https://www.eumetsat.int/website/home/News/ConferencesandEvents/DAT_4070861.html?lang=EN

![EventBanner](https://github.com/rakesh-p/Atmoshack2018/blob/master/01-images/Atmoshack2018-banner.jpg)

### Challenge
Urban air pollution poses a significant threat to human health and the quality of life of millions of people worldwide. Nine out of ten people are estimated to breathe air containing high levels of pollutants, causing around 7 million deaths every year. More than 90% of air pollution-related deaths occur in the developing world. Many of these areas have no surface air-quality monitoring networks and rely mainly on modelling and satellite information. 

Your challenge is to create solutions that help people in their daily lives to reduce their exposure to pollutants and UV radiation. To solve this challenge, you are encouraged to use Copernicus atmospheric monitoring data.

Various approaches are welcome: Create new solutions or add atmosphere-smart features to existing solutions. Propose innovative data visualisations for academic purposes or for raising awareness around the atmospheric environment. Mobile, web apps, platforms or hardware - it’s your call how to improve the quality of life for many!

### Dataset offering
An overview of the complete set of datasets available for this event is listed below

|  Product | Source | Used for   | Geo Coverage  | Time Coverage   |  Resolution |  Format | HTTP Access  |
| ------------ | ------------ | ------------ | ------------ | ------------ | ------------ | ------------ | ------------ |
|PMAP Aerosol Optical Depth - particles in the atmosphere | Metop | Air pollution (basis for PM10, PM2.5 etc) | Global | April 2016 - onwards.  Aim 2017 onwards. (14 per day). January 2017 until December 2017 | 5x40km and 10x40km | NetCDF | [GOME-PMAP](http://atmoshack.obs.eu-de.otc.t-systems.com/?prefix=01-GOME_PMAP)|
|NO2, Aerosols Index | Metop GOME-2 and IASI | Air pollution monitoring, volcanic eruptions, forest fires | Global | 2016 onwards | 40x80km | NetCDF/HDF5 | tbd
| NO2, CO, O3 |	Sentinel-5p Tropomi	| Air pollution monitoring | Global	| July 2018 onwards | 5x5km and 7x5km | NetCDF |  [Sentinel-5P](http://atmoshack.obs.eu-de.otc.t-systems.com/?prefix=03-Sentinel_5p-Tropomi/) |
|UV index (corrected for clouds with ECMWF data) | Metop (AC SAF) | UV - risk of harm | Global | June 2007 until May 2017 | 250 x 250 | PNG/HDF5 | [UV-Index](http://atmoshack.obs.eu-de.otc.t-systems.com/?prefix=02-UV_Index-AC_SAF/)|
|Dust RGB |	Meteosat Second Generation (geo orbit) | Dust storms - health and transport problems |Atlantic and Indian Ocean	| Available from 28th September 2018 | 4km | GeoTiff/PNG | [Dust-RGB](http://atmoshack.obs.eu-de.otc.t-systems.com/?prefix=04-Meteosat-Dust_RGB) |
|Ash RGB | Meteosat Second Generation (geo orbit) |	Volcanic ash - aviation, health etc. | Atlantic and Indian Ocean | Available from 28th September 2018 | 4km | GeoTiff/ PNG | [Ash-RGB](http://atmoshack.obs.eu-de.otc.t-systems.com/?prefix=05-Meteosat-Ash_RGB)|
|Regional forecasts/analyses of PM, O3, NO2, SO2 | CAMS | European air pollution | Europe | 2018 | Point data (as used in Euronews air quality forecasts), gridded data @ ~10km	| CSV , NetCDF (gridded data) | [Air-Pollution](http://atmoshack.obs.eu-de.otc.t-systems.com/?prefix=06-CAMS-AirPollution)|
|Global total ozone column | CAMS |	Total ozone columns | Global | 2003-present. Reanalysis from 2003 until 2016 | ~40km | NetCDF, GRIB |[CAMS Reanalysis data](https://confluence.ecmwf.int/display/CKB/How+to+download+the+CAMS+Reanalysis+data+via+the+ECMWF+Web+API)|
|Global UV forecasts | CAMS | UV index | Global | 2003-present. NRT from 2016 June onwards, Reanalysis from 2003 to 2016 |~40km	| NetCDF | [CAMS](https://atmosphere.copernicus.eu/) |
|Global fire emissions | CAMS |	Wildland fire emission estimates | Global |	2003-present | ~10km | NetCDF | [CAMS](https://atmosphere.copernicus.eu/) |

### Platform offering
WEkEO platform [wekeo.eu](https://www.wekeo.eu/) provides access to Copernicus datasets and cloud based processing resources. Get to know the capabilities of WEkEO from [here](https://www.wekeo.eu/documentation/getting_started)
You can request for VM access by sending the request from [here](https://www.wekeo.eu/advanced_user)

### Solution domains 
* Air-quality apps
* Traffic and navigation
* Geological: volcanic eruptions, dust and smoke in the atmosphere
* Academic purpose solutions: data visualisations, new data analysis models
* Healthcare
* Education
* Internet of Things (IOT) and combinations of ground sensors to networks
* Cleantech for industries, factories and agriculture
* Smart city solutions

### Background
Copernicus AtmosHack is funded by the EU’s [Copernicus Programme](http://www.copernicus.eu/) and has been organised through a partnership of [EUMETSAT](https://www.eumetsat.int/website/home/index.html), the [Copernicus Atmosphere Monitoring Service (CAMS)](https://atmosphere.copernicus.eu/), the [Finnish Meteorological Service (FMI)](https://en.ilmatieteenlaitos.fi/), and the [University of Helsinki](https://www.inar.helsinki.fi/).
